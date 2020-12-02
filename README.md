# FedCD: Improving Performance in non-IID Federated Learning

Presented at the KDD’20 workshop on Artificial Intelligence of Things (AIoT) on August 24 2020. Link to paper [here](https://aiotworkshop.github.io/published/CS_242_KDD_Workshop_Submission%20(4).pdf).

__Note: Code is currently being updated.__


## Abstract

Federated learning has been widely applied to enable decentralized devices, which each have their own local data, to learn a shared model. However, learning from real-world data can be challenging as it is rarely identically and independently distributed (IID) across edge devices (a key assumption for current high-performing and low-bandwidth algorithms). We present a novel approach, FedCD, which clones and deletes models to dynamically group devices with similar data. Experiments on the CIFAR-10 dataset show that FedCD achieves higher accuracy and faster convergence comparedto a FedAvg baseline on non-IID data while incurring minimal computation, communication, and storage overheads.
