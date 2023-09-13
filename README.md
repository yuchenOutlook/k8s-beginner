# Kubernetes Voting App

This repository contains a simple version of the Voting App, which was developed as a simple microservices application. The YAML files in this repository are used to deploy the Voting App in a Kubernetes cluster.

## Installation

To install the Voting App in a Kubernetes cluster, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the `k8s` directory.
3. Run the following command to deploy the Voting App:

```shell
kubectl apply -f .
```

This command will deploy all of the necessary Kubernetes resources to run the Voting App.

## Usage

To use the Voting App, follow these steps:

1. Get the IP address of the Kubernetes cluster by running the following command:

kubectl get nodes -o wide

This command will display the IP address of the Kubernetes cluster.

2. If running in minikube, Open a web browser and navigate to the IP address of the Kubernetes cluster.

```shell
minikube service voting-service
```

This will open the Voting App in your web browser.

## Contributing

If you would like to contribute to the Kubernetes Voting App, please follow these guidelines:

1. Fork this repository to your own GitHub account and then clone it to your local device.
2. Create a new branch and make your changes.
3. Test your changes thoroughly.
4. Submit a pull request to this repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
