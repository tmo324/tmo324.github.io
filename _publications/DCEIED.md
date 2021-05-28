---
title: "Design Considerations for Energy-efficient Inference on Edge Devices"
collection: publications
permalink: /publications/DCEIED
venue: "The 2nd International Workshop on Energy-Efficient Learning at the Edge"
---

## Abstract
The emergence oflow-power accelerators has enabled deep learning models to be executed on mobile or embedded edge devices without relying on cloud resources. The energy-constrained nature of these devices requires a judicious choice of a deep learning model and system configuration parameter to meet application needs while optimizing energy used during deep learning inference. In this paper, we carry out an experimental evaluation of more
than 40 popular pretrained deep learning models to characterize trends in their accuracy, latency, and energy when running on edge accelerators. Our results show that as models have grown in size, the marginal increase in their accuracy has come at a much higher energy cost. Consequently, simply choosing the most accu- rate model for an application task comes at a higher energy cost; the application designer needs to consider the tradeoff between latency, accuracy, and energy use to make an appropriate choice. Since the relation between these metrics is non-linear, we present a recommendation algorithm to enable application designers to choose the best deep learning model for an application that meets energy budget constraints. Our results show that our technique can provide recommendations that are within 3 to 7% of the specified budget while maximizing accuracy and minimizing energy.
CCS
