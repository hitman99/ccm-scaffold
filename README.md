## Kubernetes Out of Three CCM Scaffold
This is a scaffold project for Kubernetes Cloud Controller Manager for kubernetes v1.16.3.
It's a PITA to setup this at the moment due to go mod `unknown revision v0.0.0` error with multiple kubernetes dependencies.
I hope that this will be fixed in the future. For now the solution is to pin all dependencies to a specific kubernetes version,
in this case it's **v1.16.3**

### You are welcome.