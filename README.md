# Indian Sign Language
Technology has the power to do many things, and changing the world is one of them. And right now, there is an opportunity for us to help verbally challenged people to communicate with the common people. We recognise that technology alone cannot fix everything but technology can help bridge the gaps. This project is an effort to create solutions to address the challenges faced by verbally challenged people on a daily basis.

## Goal for this Project

The desired outcome of this project is to create an open source asset that can have measurable impact on the problem statements listed in this repository.

Project ISL(Indian Sign Language) is one of the initiatives where we are trying to give it back to the society. This is a project where developers code for a cause. With this project, we are trying to address the problems that verbally challenged(deaf and dumb) people go through every day. Verbally challenged people communicate using sign languages and the most commonly used sign language in south Asian countries is ISL(Indian Sign Language). While there are solutions using which we are recognising sign language but there are no standard solutions that are accessible to everyone. To address this problem, we are proposing Project ISL. The idea is to create a platform where verbally challenged can talk to regular people(and vice versa). Our plan is to infuse AI/ML techniques and create open and standard models that are publicly accessible for everyone to consume and perform translation from ISL to local languages in India(and vice versa).

## Contribute to this effort

1. **Engage**

   * Understand the [problem statements](##problem-statements) that are listed under this Github repository
   * Reach out to us and stay connected if you want to get involved in our activities


2. **Contribute**
   * IBMers: [Learn](https://w3.ibm.com/developer/opensource/learn/certify/) about open source and [certify](https://yourlearning.ibm.com/activity/EL01-00001160) before contributing.
   * If you have any questions or issues you can create a new [issue here][issues].
   * Pull requests are very welcome! Make sure your patches are well tested.
Ideally create a topic branch for every separate change you make.


3. **Steps to contribute**

   * Fork the repo
   * Create your feature branch (`git checkout -b my-new-feature`)
   * Commit your changes (`git commit -am 'Added some feature'`)
   * Push to the branch (`git push origin my-new-feature`)
   * Create new Pull Request

## Problem Statements

1. Verbally challenged people don't have a standard system using which they can communicate with people that use various common languages like English.

2. People who are working on translation systems for sign languages to common languages(and vice versa) don't have standard APIs/services to consume.

3. Creating secure translation models where we don't have to worry about model poisoning, Inference, Extraction, Evasion.

## Problem Statement - 01

### who, what and how

1. Verbally challenged people require a medium using which they can communicate with the ones who don't understand sign language, and vice versa.

2. NGOs, agencies and educational institutes require a way using which they can communicate to verbally challenged who talk sign language.

3. Training a model that can perform this translation could bridge the gap in the current ways.  

### How can Tech help?

1. [Indian Sign Language translator using Neural Machine translation ](https://github.com/Sanjay-George/isl_translator_client)

2. [Indian sign language (ISL) gestures for deaf and dumb people](https://github.com/Karthikeyu/Indian-sign-language-recognition)

3. [Automatic Translator, an application which is purposely deployed for deaf people that converts speech to text and then to Indian Sign Language gestures](https://github.com/satyam9090/Automatic-Indian-Sign-Language-Translator)

#### Available solutions

* Here is a research project called [ISL](http://www.islfromtext.in/avatarfinal.php)

#### Example Solution

* A deep learning model that recognise alphabet, vocabulary and sentences in ISL and translate them into native languages like English, Hindi, Telugu etc

### Resources Available

#### Datasets
Here are a couple of datasets we gathered

1. [Alphabet Images](https://drive.google.com/drive/folders/0B6iDOaIw70SceUFWQ0NoREVIUTA)

2. [Alphabet images of other sign languages](https://drive.google.com/open?id=1wgXtF6QHKBuXRx3qxuf-o6aOmN87t8G-)

#### User Personas

1. Citizens

    * Citizens who are verbally challenged
    * Citizens who want to communicate with verbally challenged
    * Citizens who are working for an agency that works with verbally challenged

2. NGOs and Educational Institutes for Specially Abled

    * Educational Institutions who have verbally challenged students
    * Agencies and Non Profit Organisations that are working with verbally challenged people

#### Papers and Publications

1. [Real-time Indian Sign Language (ISL) Recognition](https://ieeexplore.ieee.org/document/8493808)

2. [Hand gesture recognition for Indian Sign Language](https://ieeexplore.ieee.org/document/6158807)

3. [A comprehensive review on automation of Indian sign language](https://ieeexplore.ieee.org/document/7164682)

## Problem Statement - 02

### who, what and how

1. While there are many organisations working on sign languages, there are no standard APIs and services that are available for developers to readily consume and build a solution.

2. This problem statement aims to create a service/APIs that can be consumed by the developers/organisations working with ISL. This also aims at creating standard and reliable browser extensions, web interfaces for the models created Problem Statement 01.

3. Creation of mobile/web applications and avatars that help users to understand ISL can add on to this project's mission.

### How can Tech help?

1. [Live video feed translator for Indian Sign Language](https://github.com/AryanVerma2204/Indian_Sign_Language)

2. [Hand Pose Recognition](https://github.com/dev-td7/hand-pose-recognition-demo)

3. [Indian Sign Language Translator API](https://github.com/dev-td7/Indian-Sign-Language-Translator)

#### Available solutions

1. A [chrome extension](https://chrome.google.com/webstore/detail/convert-text-to-isl/cnjkedbgijbppmonekeajnbdokgmkekd?utm_source=chrome-ntp-icon) that converts text to ISL.

#### Example Solution

1. A web/mobile application that calls the models created in the first problem statement and shows the translated text using avatars.

### Resources Available

#### User Personas

1. Application developers

  * Developers who are building something around ISL

  * Developers who are looking for APIs to instantly consume and perform translation

2. Agencies working on Indian Sign Languages

  * Agencies who are building applications for ISL

  * Agencies that want to provide an interface for verbally challenged people within their organisation

#### Papers and Publications

1. [Indian sign language converter system using an android app](https://ieeexplore.ieee.org/document/8212852)

2. [Animation system for Indian Sign Language communication using LOTS notation](https://ieeexplore.ieee.org/document/6749444)

3. [SignQuiz: A Quiz Based Tool for Learning Fingerspelled Signs in Indian SignLanguage Using ASLR](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8657686)

## Problem Statement - 03

### who, what and hows

1. Machine learning model security is one of the major areas that should be considered while creating models.

2. Application security is one of the areas we are looking for. Since this is an opensource project and developers are welcome to commit their piece of code. While they commit their code, we would definitely want contributions around app sec practices.

### How can Tech help?

1. [Adversarial Robustness Tooklit](https://github.com/Trusted-AI/adversarial-robustness-toolbox)

2. [OWASP Application Security](https://owasp.org/www-project-appsec-pipeline/)

#### Example Solution

* Various test scripts that can check the application created

### Resources Available

#### User Personas

* Everyone involved must make sure their code is secure before committing and that's when we will merge the code they have submitted

#### Papers and Publications

* [Trusted AI and Model Securtiy](https://www.ibm.com/blogs/research/2019/09/adversarial-robustness-360-toolbox-v1-0/?_ga=2.129415310.301803852.1603968883-1193597190.1603526351)

## Usage

This repository contains:

* [LICENSE](LICENSE)
* [README.md](README.md)
* [CONTRIBUTING.md](CONTRIBUTING.md)
* [MAINTAINERS.md](MAINTAINERS.md)
* [CHANGELOG.md](CHANGELOG.md)

## License & Authors

If you would like to see the detailed LICENSE click [here](LICENSE).

- Authors: Amol Dhondse(amol.dhondse@in.ibm.com), Rachana Vishwanathula(rachvis1@in.ibm.com)

```text
Copyright:: 2020 - IBM India, Inc

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
