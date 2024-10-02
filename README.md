# FL-DABE-BC

Abstract

In IoT scenarios, where data privacy and security
are among the major concerns, FL is a decentralized training
approach that can be used to train machine learning models with-
out transferring sensitive data from IoT devices. The framework
proposed in our research advances the concept of FL for IoT
scenarios, adding the most advanced security schemes such as De-
centralized Attribute-Based Encryption (DABE) for decentralized
authentication, Homomorphic Encryption (HE), Secure Multi
Party Computation (SMPC), and Blockchain technology to secure
the entire process of modeling training against data privacy and
security issues. In this framework, data from all IoT devices are
locally encrypted using DABE for decentralized authentication
and data encryption, then based on HE, data can be securely
computed on encrypted data. Afterward, SMPC technology is
employed to preserve privacy and collaborative computations.
The output from SMPC is securely transmitted via Blockchain,
which guarantees transparent communication and data integrity
and securely stores all relevant transactions and model updates
in a distributed ledger across the entire FL network.
The framework begins with IoT devices collecting and prepar-
ing data for local model training, where the data is encrypted
using DABE. Initial deep learning models configured in cloud
servers are distributed to edge devices via a blockchain network,
ensuring immutable record-keeping and secure peer authenti
cation. After local training, the updated model weights are en
crypted and securely transmitted to fog layers via the blockchain,
where micro-services perform aggregation using homomorphic
encryption and SMPC. The FL server aggregates these local
updates with differential privacy to prevent data leakage and
iteratively refines the global model. The final global model is then
distributed back to the IoT devices for deployment, enabling real-
time analytics in IoT market spaces. This framework effectively
addresses the challenges of secure decentralized learning in IoT
environments, offering a robust solution for privacy-preserving,
efficient, and secure federated learning.

Index Terms—Federated Learning, Decentralized Attribute-
Based Encryption, Blockchain

Introduction

The Internet of Things (IoT) is a brilliant way to connect
different physical objects with digital information. Its rapid
adoption is already revolutionizing many different aspects ofdifferent industries. IoT has already resulted in amazingly
future-oriented applications, including consumer-grade home
automation and medical science. But if we want to see further
growth in these areas and move to new areas such as industrial
automation, we also need to address the key challenges of
addressing data privacy and security concerns. Centralized
machine learning models, often involving the transfer of
sensitive information from IoT devices to centralized servers,
have proven to be inadequate for these purposes. They also
potentially expose data to a variety of malicious attacks.
This has made it an increasingly urgent priority to move to
decentralized, secure learning frameworks.

FL has the potential to overcome these issues as it enables
the training of machine learning models on devices without
transferring the underlying data into a central server. This is
facilitated by the FL approach of allowing trained models
to be updated individually on IoT devices and shared with
a central server as part of the iterative aggregation process.
However, a lack of security in FL frameworks could still result
in privacy leaks and data exposure in IoT environments, which
process sensitive data. This makes it crucial to develop robust
security strategies that can be seamlessly incorporated into
FL frameworks to achieve a high level of data privacy and
integrity, such as using distributed data.



This work has been submitted to the Cluster Computing Springer Journal
