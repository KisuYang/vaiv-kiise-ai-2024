# vaiv-kiise-ai-2024

This repository contains the evaluation code for the [Generative AI Competition](https://www.kiise.or.kr/conference/main/getContent.do?CC=kcc&CS=2024&content_no=2068&PARENT_ID=012000) hosted by VAIV Company × Korean Institute of Information Scientists and Engineers (KIISE).

## Usage

The _evaluate_adapter.py_ script is used to evaluate a specific adapter on a given dataset.

To run the evaluation code, use the following command:

```sh
python evaluate_adapter.py \
  --adapter_name YOUR_ADAPTER_NAME \
  --dataset_name vaiv/ko-rag-preference \
  --dataset_split validation \
  --chatgpt_model gpt-4 \
  --chatgpt_api_key CHATGPT_API_KEY
```

## Further Information

- Competition Guidance: https://www.kiise.or.kr/conference/main/getContent.do?CC=kcc&CS=2024&content_no=2068&PARENT_ID=012000
- Frequently Asked Questions (FAQs): https://www.notion.so/VAIV-x-AI-FAQs-48e7ad7eac4140f2b5451b57fbce3d94
- Model Submission: https://forms.gle/iviGNPopkrTfojfw7
- Leaderboard: https://sites.google.com/vaiv.kr/kiise-leaderboard/
