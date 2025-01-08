<div align="center">

<img src="https://github.com/user-attachments/assets/49fe62c8-6796-4594-adda-5dac9ac64725" alt="Forebyte Logo" width="100">



# Forebyte

<p align="center">
  <a href="./README_en.md">English</a> |
  <a href="./README.md">Simplified Chinese</a> |
  <a href="./README_ja.md">Japanese</a>
</p>

Forebyte is a knowledge-based Q&A system powered by a large language model (LLM), offering out-of-the-box data processing and model-calling capabilities. It also supports visual workflow orchestration via Flow to enable complex Q&A scenarios!

</div>

<p align="center">
  <a href="https://Forebyte.fun/">
    <img height="21" src="https://img.shields.io/badge/Use%20Online-d4eaf7?style=flat-square&logo=spoj&logoColor=7d09f1" alt="cloud">
  </a>
  <a href="https://doc.tryForebyte.ai/docs/intro">
    <img height="21" src="https://img.shields.io/badge/Documentation-7d09f1?style=flat-square" alt="document">
  </a>
  <a href="https://doc.tryForebyte.ai/docs/development">
    <img height="21" src="https://img.shields.io/badge/Local%20Development-%23d4eaf7?style=flat-square&logo=xcode&logoColor=7d09f1" alt="development">
  </a>
  <a href="/#-%E7%9B%B8%E5%85%B3%E9%A1%B9%E7%9B%AE">
    <img height="21" src="https://img.shields.io/badge/Related%20Projects-7d09f1?style=flat-square" alt="project">
  </a>
</p>



## 🛸 Use Online

- 🌍 International Version: [Forebyte.fun](https://Forebyte.fun/)

<a href="#readme">
    <img src="https://img.shields.io/badge/-Back%20to%20Top-7d09f1.svg" alt="#" align="right">
</a>

## 💡 RoadMap

`1` Application Orchestration Capabilities
   - [x] Dialog workflows, plugin workflows
   - [x] Tool calling
   - [x] Code sandbox
   - [x] Loop calling
   - [x] User selection
   - [x] Form input

`2` Knowledge Base Capabilities
   - [x] Multi-library reuse and mixing
   - [x] Chunk record modification and deletion
   - [x] Supports manual input, direct segmentation, QA split import
   - [x] Supports txt, md, html, pdf, docx, pptx, csv, xlsx (can PR more file loaders), URL reading, CSV batch import
   - [x] Mixed retrieval & re-ranking
   - [x] API knowledge base
   - [ ] Custom file reading service
   - [ ] Custom chunking service
  
`3` Application Debugging Capabilities
   - [x] Single-point search test in the knowledge base
   - [x] Feedback and modification during dialogs
   - [x] Full context display
   - [x] Full module intermediate value display
   - [ ] Advanced orchestration debug mode
  
`4` OpenAPI Interface
   - [x] Completions interface (chat mode aligned with GPT interface)
   - [x] Knowledge base CRUD
   - [x] Dialog CRUD
  
`5` Operational Capabilities
   - [x] Shareable window without login
   - [x] One-click embed via Iframe
   - [x] Chat window embed with custom icons, default opening, dragging, etc.
   - [x] Unified dialog history review and data annotation
   
`6` Miscellaneous
   - [x] Supports voice input and output (configurable)
   - [x] Fuzzy input suggestions
   - [x] Template marketplace

<a href="#readme">
    <img src="https://img.shields.io/badge/-Back%20to%20Top-7d09f1.svg" alt="#" align="right">
</a>

## 👨‍💻 Development

Project tech stack: NextJs + TS + ChakraUI + MongoDB + PostgreSQL (PG Vector plugin)/Milvus

- **⚡ Quick Deployment**

  > Deploy via [Sealos](https://sealos.io) without server purchase or domain name. Supports high concurrency and dynamic scaling. Database applications use Kubeblocks for superior IO performance compared to simple Docker container deployment.

  [Click here for the Forebyte one-click deployment tutorial via Sealos](https://doc.tryForebyte.ai/docs/development/sealos/)

* [Quick Start for Local Development](https://doc.tryForebyte.ai/docs/development/intro/)
* [Deploy Forebyte](https://doc.tryForebyte.ai/docs/development/sealos/)
* [System Configuration Guide](https://doc.tryForebyte.ai/docs/development/configuration/)
* [Multi-Model Configuration Guide](https://doc.tryForebyte.ai/docs/development/modelconfig/one-api/)
* [Version Update/Upgrade Instructions](https://doc.tryForebyte.ai/docs/development/upgrading/)
* [OpenAPI API Documentation](https://doc.tryForebyte.ai/docs/development/openapi/)
* [Knowledge Base Structure Guide](https://doc.tryForebyte.ai/docs/guide/knowledge_base/rag/)

<a href="#readme">
    <img src="https://img.shields.io/badge/-Back%20to%20Top-7d09f1.svg" alt="#" align="right">
</a>

## 🏘️ Community Group

Scan to join the Feishu topic group:

![](https://oss.laf.run/otnvvf-imgs/Forebyte-feishu1.png)

<a href="#readme">
    <img src="https://img.shields.io/badge/-Back%20to%20Top-7d09f1.svg" alt="#" align="right">
</a>

## 🏘️ Join Us

We are looking for like-minded individuals to accelerate Forebyte's development. Learn more about [Forebyte 2025 Recruitment](https://fael3z0zfze.feishu.cn/wiki/P7FOwEmPziVcaYkvVaacnVX1nvg).

## 💪 Related Projects

- [Laf: Quick integration with third-party applications in 3 minutes](https://github.com/labring/laf)
- [One API: Multi-model management supporting Azure, Baidu Wenxin, etc.](https://github.com/songquanpeng/one-api)
- [TuShan: Build a backend management system in 5 minutes](https://github.com/msgbyte/tushan)

<a href="#readme">
    <img src="https://img.shields.io/badge/-Back%20to%20Top-7d09f1.svg" alt="#" align="right">
</a>

## 🌿 Third-Party Ecosystem

- [COW Personal/Enterprise WeChat Bot](https://doc.tryForebyte.ai/docs/use-cases/external-integration/onwechat/)
- [SiliconCloud – Open-source Model Experience Platform](https://cloud.siliconflow.cn/i/TR9Ym0c4)

<a href="#readme">
    <img src="https://img.shields.io/badge/-Back%20to%20Top-7d09f1.svg" alt="#" align="right">
</a>

## 👀 Additional Resources

- [Comprehensive Forebyte Tutorial](https://www.bilibili.com/video/BV1n34y1A7Bo/?spm_id_from=333.999.0.0)
- [Feishu Integration](https://www.bilibili.com/video/BV1Su4y1r7R3/?spm_id_from=333.999.0.0)
- [Enterprise WeChat Integration](https://www.bilibili.com/video/BV1Tp4y1n72T/?spm_id_from=333.999.0.0)

<a href="#readme">
    <img src="https://img.shields.io/badge/-Back%20to%20Top-7d09f1.svg" alt="#" align="right">
</a>

## 🤝 Contributing

We welcome all forms of contribution. If you’re interested in contributing code, check out our GitHub [Issues](https://github.com/labring/Forebyte/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc) to showcase your creativity and ideas.

<a href="https://github.com/labring/Forebyte/graphs/contributors" target="_blank">
  <table>
    <tr>
      <th colspan="2">
        <br><img src="https://contrib.rocks/image?repo=labring/Forebyte"><br><br>
      </th>
    </tr>
    <tr>
      <td>
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://next.ossinsight.io/widgets/official/compose-org-active-contributors/thumbnail.png?activity=active&period=past_28_days&owner_id=102226726&repo_ids=605673387&image_size=2x3&color_scheme=dark">
          <img alt="Active participants of labring - past 28 days" src="https://next.ossinsight.io/widgets/official/compose-org-active-contributors/thumbnail.png?activity=active&period=past_28_days&owner_id=102226726&repo_ids=605673387&image_size=2x3&color_scheme=light">
        </picture>****
      </td>
      <td rowspan="2">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://next.ossinsight.io/widgets/official/compose-org-participants-growth/thumbnail.png?activity=new&period=past_28_days&owner_id=102226726&repo_ids=605673387&image_size=4x7&color_scheme=dark">
          <img alt="New trends of labring" src="https://next.ossinsight.io/widgets/official/compose-org-participants-growth/thumbnail.png?activity=new&period=past_28_days&owner_id=102226726&repo_ids=605673387&image_size=4x7&color_scheme=light">
        </picture>
      </td>
    </tr>
    <tr>
      <td>
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://next.ossinsight.io/widgets/official/compose-org-active-contributors/thumbnail.png?activity=new&period=past_28_days&owner_id=102226726&repo_ids=605673387&image_size=2x3&color_scheme=dark">
          <img alt="New participants of labring - past 28 days" src="https://next.ossinsight.io/widgets/official/compose-org-active-contributors/thumbnail.png?activity=new&period=past_28_days&owner_id=102226726&repo_ids=605673387&image_size=2x3&color_scheme=light">
        </picture>
      </td>
    </tr>
  </table>
</a>

<a href="#readme">
    <img src="https://img.shields.io/badge/-Back%20to%20Top-7d09f1.svg" alt="#" align="right">
</a>

## License

This repository follows the [Forebyte Open Source License](./LICENSE).

