<img width="1387" height="781" alt="image" src="https://github.com/user-attachments/assets/4bb094b8-09a4-4fb3-a390-37fbc0955a58" />



###  OpenFunction | Kubernetes ☸️
OpenFunction is a cloud-native open source FaaS (Function as a Service) platform aiming to let you focus on your business logic without having to maintain the underlying runtime environment and infrastructure. You only need to submit business-related source code in the form of functions.


🧱 Key Features:
```
✅ Cloud agnostic and decoupled with cloud providers' BaaS
✅ Pluggable architecture that allows multiple function runtimes
✅ Support both sync and async functions
✅ Unique async functions support that can consume events directly from event sources
✅ Support generating OCI-Compliant container images directly from function source code.
✅ Flexible autoscaling between 0 and N
✅ Advanced async function autoscaling based on event sources' specific metrics
✅ Simplified BaaS integration for both sync and async functions by introducing Dapr
✅ Advanced function ingress & traffic management powered by K8s Gateway API
✅ Flexible and easy-to-use events management framework
```

## Example

### AWS
```

```
### Google
```

```

🔨 Config :
```
terraform init
terraform validate
terraform plan -var-file="template.tfvars"
terraform apply -var-file="template.tfvars" -auto-approve
```
