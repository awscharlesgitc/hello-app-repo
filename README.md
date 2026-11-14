You need two separate GitHub repositories to implement the GitOps flow correctly:

hello-app-repo: Contains your application source code, Dockerfile, Helm chart, and the GitHub Actions workflow (CI).

hello-infra-repo: Contains the Terraform code for the EKS cluster and the Argo CD Application manifest (CD).
