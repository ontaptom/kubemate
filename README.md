# kubemate - K8s Assistant

kubemate is a tool that helps you manage your Kubernetes (K8s) resources. It uses OpenAI's powerful language models to understand what you want to do, and then generates YAML file that can be applied. If you like the proposed outcome, kubemate can also execute the commands for you!

## Work in progress

This project is still under development phase. Use it at your own risk.

## Updates

### [07.11.2023] OpenAI library update

On November 6th OpenAI has released OpenaI Python API library in version => 1.0.0. Currently `kubemate` is using that library, and is calling model `gpt-3.5-turbo` which is proven to be highly effective for Kubernetes-related tasks. It can efficiently produce YAML configuration files for Kubernetes resources, offering an automated and error-free approach to managing these configurations. Additionally, it is adept at explaining questions, errors, and misconfigured YAML files, providing clear and concise explanations and solutions. 

## Contributing

If you find a bug or have a feature request, please open an issue on the kubemate GitHub repository: https://github.com/ontaptom/kubemate

Pull requests are also welcome! If you want to contribute to kubemate, please fork the repository, create a new branch, and then submit a pull request. Please ensure that your code passes the existing tests and linting rules.

## License

This project is licensed under the terms of the Apache License 2.0. See the `LICENSE` file for more details.