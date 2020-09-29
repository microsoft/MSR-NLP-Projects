# Microsoft Research NLP Projects

This is a list of open-sourced projects [Microsoft Research NLP Group](https://www.microsoft.com/en-us/research/group/natural-language-processing) involved. (ranked in time order)

## Datasets
| Title    | Description | Related projects | 
| :------------- | :----------- | :----------- | 
| [Dialogue Feedback Dataset](https://dialogfeedback.github.io/) | 100+ Millions of dialogues with corresponding human feedback to learn which one gets better feedback | [DialogRPT](https://github.com/golsun/DialogRPT) |
| [Grounded Dialogue Dataset](https://github.com/mgalley/DSTC7-End-to-End-Conversation-Modeling) | Dialogues with information grounded in external knowledge, e.g. wikipedia pages | [DSTC7](https://github.com/mgalley/DSTC7-End-to-End-Conversation-Modeling), [CMR](https://github.com/qkaren/converse_reading_cmr) |
| [Reddit Dialogue Dataset](https://github.com/microsoft/DialoGPT) | 147M conversation-like exchanges extracted from Reddit comment chains over a period spanning from 2005 through 2017 | [DialoGPT](https://github.com/microsoft/DialoGPT) |

## Papers
| Title    | Links | Notes | Tags |
| :------------- | :-----------: | :-----------: |:-----------: |
| [Dialogue Response Ranking Training with Large-Scale Human Feedback Data](https://arxiv.org/abs/2009.06978) | [code/model/data](https://github.com/golsun/DialogRPT), [demo](https://colab.research.google.com/drive/1jQXzTYsgdZIQjJKrX4g3CP0_PGCeVU3C?usp=sharing) | EMNLP 2020 | `dialog` `ranking`|
| [POINTER: Constrained Text Generation via Insertion-based Generative Pre-training](https://arxiv.org/abs/2005.00558) | [code](https://github.com/dreasysnail/POINTER), [demo](http://52.247.25.3:8900/) | EMNLP 2020 | `generation` |
| [Optimus: Organizing Sentences via Pre-trained Modeling of a Latent Space](https://arxiv.org/abs/2004.04092) | [code](https://github.com/ChunyuanLI/Optimus), [demo](http://40.71.23.172:8899/) | EMNLP 2020 | `generation` |
| [RAT-SQL: Relation-Aware Schema Encoding and Linking for Text-to-SQL Parsers](https://arxiv.org/abs/1911.04942) | [code](https://github.com/microsoft/rat-sql) | ACL 2020 | `parsing`, `sql`|
| [A Recipe for Creating Multimodal Aligned Datasets for Sequential Tasks](https://arxiv.org/pdf/2005.09606.pdf) | [code](https://github.com/microsoft/multimodal-aligned-recipe-corpus) | ACL 2020 | `multimodal` |
| [INSET: Sentence Infilling with INter-SEntential Transformer](https://arxiv.org/abs/1911.03892) | [code/demo](https://github.com/dreasysnail/INSET) | ACL 2020 | `generation`|
| [DialoGPT: Large-Scale Generative Pre-training for Conversational Response Generation](https://arxiv.org/abs/1911.00536) | [code/model/data](https://github.com/microsoft/DialoGPT) | ACL 2020 | `dialog` `generation`|
| [MixingBoard: a Knowledgeable Stylized Integrated Text Generation Platform](https://arxiv.org/abs/2005.08365) | [code](https://github.com/microsoft/MixingBoard) | ACL 2020 | `dialog` `generation` `framework` `knowledge` `style` |
| [Vision-based Navigation with Language-based Assistance via Imitation Learning with Indirect Intervention](https://arxiv.org/abs/1812.04155)| [code/data](https://github.com/debadeepta/vnla) | CVPR 2019 | `navigation` `imitation learning` |
| [Conversing by Reading: Contentful Neural Conversation with On-demand Machine Reading](https://www.aclweb.org/anthology/P19-1539/) | [code/model/data](https://github.com/qkaren/converse_reading_cmr) | ACL 2019 | `knowledge` `dialog` `generation`  |
| [Microsoft Icecaps: An Open-Source Toolkit for Conversation Modeling](https://www.aclweb.org/anthology/P19-3021.pdf) | [code](https://github.com/microsoft/icecaps) | ACL 2019 | `dialog` `generation` `framework` |
| [Structuring Latent Spaces for Stylized Response Generation](https://arxiv.org/abs/1909.05361) | [code/data](https://github.com/golsun/StyleFusion) | EMNLP 2019 | `style` `dialog` `generation` |
| [Jointly Optimizing Diversity and Relevance in Neural Response Generation](https://arxiv.org/abs/1902.11205) | [code/data](https://github.com/golsun/SpaceFusion) | NAACL 2019 | `dialog` `generation` |
| [Towards Content Transfer through Grounded Text Generation](https://arxiv.org/abs/1905.05293) | [code/data](https://github.com/shrimai/Towards-Content-Transfer-through-Grounded-Text-Generation) | NAACL 2019 | `generation` `knowledge`|

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

# Legal Notices

Microsoft and any contributors grant you a license to the Microsoft documentation and other content
in this repository under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode),
see the [LICENSE](LICENSE) file, and grant you a license to any code in the repository under the [MIT License](https://opensource.org/licenses/MIT), see the
[LICENSE-CODE](LICENSE-CODE) file.

Microsoft, Windows, Microsoft Azure and/or other Microsoft products and services referenced in the documentation
may be either trademarks or registered trademarks of Microsoft in the United States and/or other countries.
The licenses for this project do not grant you rights to use any Microsoft names, logos, or trademarks.
Microsoft's general trademark guidelines can be found at http://go.microsoft.com/fwlink/?LinkID=254653.

Privacy information can be found at https://privacy.microsoft.com/en-us/

Microsoft and any contributors reserve all other rights, whether under their respective copyrights, patents,
or trademarks, whether by implication, estoppel or otherwise.
