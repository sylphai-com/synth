Open-source ML Platform Framework- Synth

## About

`synth` is an open-source framework that helps ML teams to jump start their internal MLOps platform building process and speed up their ML innovations. `synth` is short for synthesizer, which is used to compose music; in ML, we envision `synth` is used to “compose” a robust ML platform.

## Vision

Our vision and requirement for the internal MLOps platform are to support both batch and real-time ML predictions; this ML platform should be flexible, scalable, transparent (easy to debug), vendor-agnostic, infrastructure-agnostic, and developer-friendly, more collaborative. Most importantly, we will build out all components in the ML platform completely with open sources. Moreover, the key to productivity and quality is allowing developers or researchers to use powerful tools they are familiar with, such as VS code, rather than getting trapped in a vendor-hosted Jupyter notebook. 

The different phases of the ML platform varies for different companies. For companies who dont have training data and who dont need AI at the beginning and companies who are selling AI solutions and have training data, their phases can differ. We decide to define the Phase following the data gathering trajectory.

## Phases

We build our MLOps platform in phases, as in the beginning we only had a few small ML models in production to support our product. As we scale to support growing users and product functions, the MLOps requirement would change. Below is the roadmap of this MLOps platform framework:

### Phase 0: Out-of-box APIs + training data gathering (0 training data, 0 model in production)
* Leverage OpenAI's API's to directly serve NLP use cases such as: recommendatation using embedding or content creation using Generative AI. Check out [Chip's tutorial on Building LLM applications for production.](https://huyenchip.com/2023/04/11/llm-engineering.html)
* (Coming soon) How to use AWS amplify lambda function to quickly build your AI use case? 


**The mistake we made is to jump to Phase 1 before we come back to the out-of-box Phase 0**


### Phase 1: Deployment capabilities (~5 models in production)
You might want to opt for open source models, deploying them to save cost or improve on the performance.
* Develop simple ML models locally
* Deploy as AWS Lambda (serverless) 

### Phase 2: Train capabilities (decent amount of training data)
* local or cloud compute instance training
* train classical ML models like SVM.
* train medium size ML model
* train large size ML model

### Phase 3: Optimize the pipeline
* Set up Ray ecosystem in Kubernetes
* Train models with Ray for distributed computing
* Set up data infrastructure
* Standardize CI/ CD process
* Dedicated cloud endpoint API 

### Phase 4: Scale
* Set up ML pipeline and experiment tracking
* Feature store/ feature platform
* Drift monitoring

We are still in the process of building out the `synth` framework. We are currently in Phase 2. For each phase, we will share the code template for infrastructure, as well as detailed tutorials.

## Working group and contributors

We welcome contributors (guide). If you have built an internal ML platform and would like to contribute, please reach out, we’d love to get your feedback too. We have regular working group sessions. The next group session will be held in late March 2023, please join us!

Past working group sessions (meeting notes [here](https://docs.google.com/document/d/1ASyLiqwBTqdBQn0-T_2wG-NxmAuRuhkwPuYxTbRuquU/edit), slides [here](https://docs.google.com/presentation/d/15CogvnpBLcganbMTtP2yHBiNi3Nm5RNMd5Cd1-WIm4Q/edit#slide=id.p)):
 
* 01/17/2023 takeaways: think about data infrastructure first.
* 01/20/2023 takeaways: start small, build out in phases.

If you are interested in contributing to `synth` project, please check out the [Contributor Guide](https://github.com/sylphai-com/synth/blob/main/contributing.md) and the [Code of Conduct](https://github.com/sylphai-com/synth/blob/main/code-of-conduct.md).


## Discord community

We also have a dedicated Discord channel to coordinate the project and working group. You can join [here](https://discord.gg/Sw2dKjxVqU).

## Contacts

zac@sylphai.com; mani@sylphai.com

## [License](https://github.com/sylphai-com/synth/blob/main/LICENSE)

Apache 2.0 License.

