**[awesome-audio-driven-digital-human](https://github.com/ykk648/awesome-audio-driven-digital-human)**



### Introduction

聚焦语音驱动数字人行业内进展，国内外主要知名产品形态，开源代码和具有影响力的论文。



Focusing on the progress of the audio-driven digital human industry, the major well-known products, open-source codes, and influential papers in both domestic and foreign markets.



目前基于audio2face的数字人已经比较成熟，分为FOM/GAN/Nerf等路线，应用在直播带货、口播视频生成、广告生成等领域，一些最新的进展包括引入LLM大模型能力做在线互动、与文案生成视频结合等。



Currently, the digital humans based on audio2face have become quite  mature and are divided into routes such as FOM/GAN/Nerf. They are  applied in areas such as live streaming e-commerce, voice-over video  generation, and advertising production. Some of the latest advancements  include the introduction of large LLM models for online interactivity,  and combining video creation with copywriting.



### Products

排名不分先后

#### Domestic

|                                                              | brightened dot     | tech details (by guess) |
| ------------------------------------------------------------ | ------------------ | ----------------------- |
| [像衍科技](https://neural-avatar.com/video)                  |                    | wav2lip                 |
| [魔珐科技](https://www.xmov.ai/person/)                      | Virtual IP         | template matching       |
| [元境科技](https://www.metazen-tech.com/index.php/meta-joy/) | ChatGPT            | wav2lip                 |
| [硅基智能](https://www.guiji.ai/#/live)                      | realtime, deepfake | wav2lip                 |
| [aibote](http://www.aibote.net/metahuman.html)               | realtime, ChatGPT  | template matching       |
|                                                              |                    |                         |

#### Foreign

|                                   | brightened dot                         | tech details (by guess) |
| --------------------------------- | -------------------------------------- | ----------------------- |
| [Heygen](https://www.heygen.com/) | multilingual, talking head, deepfake   | wav2lip/FOM             |
| [D-ID](https://www.d-id.com/)     | talking head, ChatGPT, nearly realtime | FOM                     |
|                                   |                                        |                         |



### Codes & Papers

#### Talking Head

|                                                      | brightened dot                                      |      |
| ---------------------------------------------------- | --------------------------------------------------- | ---- |
| [SadTalker](https://github.com/OpenTalker/SadTalker) | sd extension, combine wav2lip&Deep3DRecon(PIRender) | 2023 |
|                                                      |                                                     | 2022 |
| [PIRender](https://github.com/RenYurui/PIRender)     | Deep3DRecon as intermediate representation          | 2021 |
| [ADNerf](https://github.com/YudongGuo/AD-NeRF)       | nerf                                                | 2021 |

#### Face Reconstruction

|                                                              | brightened dot                         |      |
| ------------------------------------------------------------ | -------------------------------------- | ---- |
| [HRN](https://github.com/youngLBW/HRN)                       | [REALY](https://realy3dface.com/) SOTA | 2023 |
| [MICA](https://github.com/Zielon/MICA)                       |                                        | 2022 |
| [DECA](https://github.com/yfeng95/DECA)                      | FLAME, detail loss                     | 2021 |
| [Deep3DFaceRecon_pytorch](https://github.com/sicxu/Deep3DFaceRecon_pytorch) | robust                                 | 2019 |

#### Voice Conversion

|                                                              | brightened dot                      |      |
| ------------------------------------------------------------ | ----------------------------------- | ---- |
| [so-vits-svc-fork](https://github.com/voicepaw/so-vits-svc-fork) | Diffusion, singing voice conversion | 2023 |
|                                                              |                                     |      |
|                                                              |                                     |      |

