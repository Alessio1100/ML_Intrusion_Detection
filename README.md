# Binary Classification of Network Flows using the NSL-KDD Dataset
## Overview 

This project aims to perform binary classification (normal vs. attack) on the NSL-KDD dataset. The NSL-KDD dataset is a widely recognized benchmark for intrusion detection systems, containing network flow records with various features describing traffic behavior. Each flow is labeled as either "normal" or as one of several attack types.

## Goal
Convert the multi-class labeling into a binary classification problem:
   - Normal: labeled as "normal"
   - Attack: any label other than "normal" is considered an attack

## Tasks
Build at least two different machine learning models to classify network flows as normal or attack.
Treat all non-"normal" flows as attacks.

## Dataset
- Input: KDDTrainClean.csv (NSL-KDD dataset)
- Features: Various attributes of each network flow (e.g., duration, protocol_type, service, flag, byte counts, error rates).
- Label: The label column indicates if the flow is normal or an attack type.

[Presentation](ML Presentation.pdf)
