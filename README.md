# FlowMeter
FlowMeter is an experimental utility built for analysing and classifing packets by looking at packet headers. 

## Primary design goals:

FlowMeter aims to:

 - **Classify packets and flows as benign or malicious with high true positives (TP) and low false positives (FP)**. 
 - **Use the labeled data to reduce amount of traffic requiring deeper analysis**. 

Additionally, Deepfence FlowMeter also categorizes packets into flows and shows a rich ensemble of flow data and statistics.

| <img width="1559" alt="Flowmeter-flows" src="https://user-images.githubusercontent.com/26308648/165219276-e9c9a99a-1bc1-40c9-bfaa-779b6380ae67.png"> |
|:--:| 
| *FlowMeter takes packets and returns file with statistics of flows.* |

| <img width="1559" alt="Flowmeter-flowsClassification" src="https://user-images.githubusercontent.com/26308648/165219569-42a84939-8c28-4b70-b864-f4980c3ee27d.png">
|:--:|
| *Flowmeter takes packets and returns file with statistics of flows and classifies packets as benign or malicious.*  |

## When to use FLowMeter

Use FlowMeter if you wish to build and operate machine-learning models on network packet data.

## Quick Start

![FlowMeter QuickStart](docs/docs/flowmeter/img/flowmeter.svg)

## Who uses FlowMeter?

 * We use FlowMeter internally to quickly analyse and label packets. It forms one part of a project to build a fast pre-filter for packets before we conduct deeper layer-7 analysis in [Deepfence ThreatMapper].
