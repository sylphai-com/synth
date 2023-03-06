# SylphAI ML Platform Framework- Synth

![image](logo-1.svg)

## About

`synth` is an open-source framework that helps ML teams to jump start their internal MLOps platform building process and speed up their ML innovations.

`synth` is started by SylphAI’s ML team, aiming to share our MLOps journey with the ML community. SylphAI is building a flexible work platform that is powered by state-of-the-art ML models, LLM (Large Language Model), and their APIs, therefore, having a robust MLOps infrastructure is essential to iterate ML lifecycle efficiently within our ML team as well as ensure high-quality user experiences on our product. 

SylphAI is a tech startup with a small ML team, therefore, this framework would be best for startups, however, we believe some principles can be applied to larger companies who just start out with ML. 

## Vision

Our vision and requirement for the internal MLOps platform are to support both batch and real-time ML predictions; this ML platform should be flexible, scalable, transparent (easy to debug), vendor-agnostic, infrastructure-agnostic, and developer-friendly, more collaborative. Most importantly, we will build out all components in the ML platform completely with open sources. Moreover, the key to productivity and quality is allowing developers or researchers to use powerful tools they are familiar with, such as VS code, rather than getting trapped in a vendor-hosted Jupyter notebook. 

## Phase

We build our MLOps platform in phases, as in the beginning we only had a few small ML models in production to support our product. As we scale to support growing users and product functions, the MLOps requirement would change. Below is the roadmap of this MLOps platform framework:

### Phase 1: Start small (3+ models in production)
* Develop simple ML models locally
* Deploy as AWS Lambda (serverless) 

### Phase 2: Better infrastructure (10+ models in production)
* Set up Ray ecosystem in Kubernetes
* Train models with Ray for distributed computing
* Set up data infrastructure
* Standardize CI/ CD process
* Dedicated cloud endpoint API 

### Phase 3: Scale
* Set up ML pipeline and experiment tracking
* Feature store/ feature platform
* Drift monitoring

We are still in the process of building out the Synth framework. We are currently in Phase 2. For each phase, we will share the code template for infrastructure, as well as detailed tutorials.

## Working group and contributors

We welcome contributors (guide). If you have built an internal ML platform and would like to contribute, please reach out, we’d love to get your feedback too. We have regular working group sessions. The next group session will be held in late March 2023, please join us!

Past working group sessions (meeting notes [here](https://docs.google.com/document/d/1ASyLiqwBTqdBQn0-T_2wG-NxmAuRuhkwPuYxTbRuquU/edit), slides [here](https://docs.google.com/presentation/d/15CogvnpBLcganbMTtP2yHBiNi3Nm5RNMd5Cd1-WIm4Q/edit#slide=id.p)):
 
* 01/17/2023 takeaways: think about data infrastructure first.
* 01/20/2023 takeaways: start small, build out in phases.

## Discord community

We also have a dedicated Discord channel to coordinate the project and working group. You can join [here](https://discord.gg/Sw2dKjxVqU).

## Contacts

zac@sylphai.com; li@sylphai.com; mani@sylphai.com

## [License](https://github.com/gohypergiant/AutoDC/blob/stable/LICENSE)

Apache 2.0 License.

