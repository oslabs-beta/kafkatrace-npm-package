# KafkaTrace
<div align="center">
<img width="364" alt="image" src="https://github.com/oslabs-beta/KafkaTrace/blob/dev/public/assets/LogoWithText-Blue.jpg?raw=true">
</div>

## Table of Contents
- [About Kafka Trace](#about-kafka-trace)
- [Tech Stacks](#tech-stacks)
- [Features](#features)
- [User Guide](#user-guide)
- [Authors](#authors)
- [License](#license)

## About KafkaTrace
Based on OpenTelemetry's standards, KafkaTrace streamlines the process of visualizing your Apache Kafka Clients by packaging together the necessary instrumentation files with popular open source monitoring UIs (Jaeger, Zipkin, and Prometheus). This documentation describes how to implement KafkaTrace.

For more information, [visit our website].

## Tech Stacks
<div align="center" width="100%">
            
[![Typescript][TS.js]][TS-url][![JavaScript][JavaScript]][JavaScript-url][![React][React.js]][React-url][![Prometheus][Prometheus]][Prometheus-url][![Zipkin][Zipkin]][Zipkin-url][![Jaeger][Jaeger]][Jaeger-url][![OpenTelemetry][OpenTelemetry]][OpenTelemetry-url][![Jest][Jest]][Jest-url][![][Git]][Git-url][![Tailwind][Tailwind]][Tailwind-url][![DaisyUI][DaisyUI]][DaisyUI-url][![NextJS][NextJs]](NextJS-url)[![NextAuth][NextAuth]][NextAuth-url][![KafkaJS][KafkaJS]][KafkaJS-url][![Docker][Docker]][Docker-url][![AWS][AWS]][AWS-url]

</div>

## Features
- Intuitive all-in-one documentation to implement distributive tracing for Kafka.
- Authentication for Google and GitHub OAuth.

## User Guide
#### Prerequisites:
You must have Docker Desktop installed and running!
<br></br>	

**IMPORTANT REMINDER**: Make sure the Kafka Cluster you want to trace has a working producer and consumer client.

- **STEP 1**: Install npm package
    ```bash
    npm install kafkatrace
    ```
- **STEP 2**: Build and run the preconfigured containers
    ```typescript
    import { composer } from 'kafkatrace';
    composer();
    ```
- **STEP 3**: Add to each service file and replace [Service Name] as required
    ```typescript
    import { tracer } from 'kafkatrace';
    tracer('[Service Name]');
    ```
- **STEP 4**: Navigate to localhost port: 16686 for Jaeger, 9411 for Zipkin, 9090 for Prometheus or simply login to the website

![demo-vid](https://github.com/oslabs-beta/kafkatrace-npm-package/assets/101201710/393720f4-597f-4439-87de-8b8fd60e655a)


## Authors
| Developed By |                                                                     Github                                                                      |                                                                   LinkedIn                                                                    |
| :----------: | :---------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------: |
|  Felix Chen  |    [![Github](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/flexzchen)    | [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/felixzchen/) |
| Navdeep Simmack | [![Github](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NaviSimmak) |  [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/Navdeep-Simmak)  |
|  Wai San Gu  |  [![Github](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/waisangu)   | [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/waisangu/) |
| Alston Nguyen  |  [![Github](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/alstonnguyen)   |  [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alston-s-nguyen/)   |


## License
Distributed under MIT License. See `LICENSE.txt` for more information.

[visit our website]: https://kafkatrace.com
[React.js]: https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB
[React-url]: https://reactjs.org/
[TS.js]: https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white
[TS-url]: https://www.typescriptlang.org/
[Prometheus]: https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white
[Prometheus-url]: https://prometheus.io/
[Zipkin]: https://img.shields.io/badge/zipkin-%23593d88.svg?style=for-the-badge&logo=zipkin&logoColor=white
[Zipkin-url]:https://zipkin.io/
[Jaeger]:https://img.shields.io/badge/Jaeger-%23F46800.svg?style=for-the-badge&logo=Jaeger&logoColor=white
[Jaeger-url]:https://www.jaegertracing.io/
[OpenTelemetry]:https://img.shields.io/badge/OpenTelemetry-3d348b?style=for-the-badge&logo=opentelemetry&logoColor=white
[OpenTelemetry-url]:https://opentelemetry.io/
[JavaScript]: https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E
[JavaScript-url]: https://www.javascript.com/
[Jest]: https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white
[Jest-url]: https://jestjs.io/
[Docker]: https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white
[Docker-url]: https://www.docker.com/
[Git]: https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white
[Git-url]: https://git-scm.com/
[Tailwind]: https://img.shields.io/badge/Tailwind-%231DA1F2.svg?style=for-the-badge&logo=tailwind-css&logoColor=white
[Tailwind-url]: https://tailwindcss.com/
[DaisyUI]:https://img.shields.io/badge/DaisyUI-%23593d88.svg?style=for-the-badge&logo=DaisyUI&logoColor=white
[DaisyUI-url]:https://daisyui.com/
[NextJS]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[NextJS-url]: https://nextjs.org/
[Prisma]: https://img.shields.io/badge/Prisma-%233b3e44?style=for-the-badge&logo=prisma&logoColor=white
[Prisma-url]: https://www.prisma.io/
[NextAuth]: https://img.shields.io/badge/NextAuth-%23F05033.svg?style=for-the-badge&logo=nextdotjs&logoColor=white
[NextAuth-url]: https://next-auth.js.org/
[KafkaJS]: https://img.shields.io/badge/KafkaJS-%2316AB39.svg?style=for-the-badge&logo=kafkajs&logoColor=white
[KafkaJS-url]: https://kafka.js.org/
[AWS]: https://img.shields.io/badge/AWS-%231E73BE.svg?style=for-the-badge&logo=amazon-aws&logoColor=white:
[AWS-url]: https://aws.amazon.com/
