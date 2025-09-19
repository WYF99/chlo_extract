# Characterizing User Platforms for Video Streaming in Broadband Networks

_Yifan Wang, Minzhao Lyu, Vijay Sivaraman_

In Proc. ACM Internet Measurement Conference (IMC), Madrid, Spain, 2024

https://doi.org/10.1145/3646547.3688435

arXiv version: https://arxiv.org/pdf/2408.16995

---

```
@inproceedings{wang_characterizing_2024,
  author = {Wang, Yifan and Lyu, Minzhao and Sivaraman, Vijay},
  booktitle = {Proc. ACM Internet Measurement Conference (IMC)},
  title = {{Characterizing User Platforms for Video Streaming in Broadband Networks}},
  year = {2024},
  month = nov,
  address = {Madrid, Spain},
  doi = {10.1145/3646547.3688435},
}
```

---

This repo contains code for extracting handshake attributes from video flows.

The training dataset containing video flows of YouTube, Netflix, Disney+ and Amazon Prime Video across user platforms is shared on our university cloud drive and can be accessed here:
https://minzhaolyu.github.io/dataset/MultimediaNetworkTrafficDataset.

The dataset is organized as follows:
```
data/
├── <video_provider>/
│   ├── <device_type>/
│   │   ├── <software_agent_1>.pcapng
│   │   ├── <software_agent_2>.pcapng
│   │   ├── ...
│   │   └── <software_agent_N>.pcapng
│   └── ...
└── ...
```

For further data enquiries, please contact the corresponding author, [Minzhao Lyu](mailto:minzhao.lyu@unsw.edu.au).
