# wine enthusiast사이트의 'wine review' 데이터셋을 활용한 와인 취향 추천
BERT를 사용한 와인취향 text 분석 추천 시스템
와인샵의 인력이 부족해서 고객에게 설명을 제대로 해주지 못하거나 교육이 제대로 되지 않은 사람이 적절하지 못한 와인을 추천해주는것은 와인 판매에 부정적인 영향을 미치고 결국 고객의 구매까지 이어지지 못하게 됩니다. 

따라서 우선 Text 분석을 통하여 고객이 원하는 와인의 품종을 예측하여 추천하게 된다면 구매를 증진 할 수 있다고 생각하여 시작하였습니다.

본 프로젝트는 colab으로 작성하였습니다. 

사용데이터: WineEnthusiast 의 1,300,000건의 와인 설명 및 리뷰 데이터
https://drive.google.com/file/d/1HnvXx6UGPra8wI3B3_HdjEiCZCttPtab/view?usp=sharing

이용한 모델:  19년 6월 1일 업데이트된 Bert-base language model
- [BERT-Large, Uncased (Whole Word Masking)](https://storage.googleapis.com/bert_models/2019_05_30/wwm_uncased_L-24_H-1024_A-16.zip)
  : 24-layer, 1024-hidden, 16-heads, 340M parameters
- https://github.com/google-research/bert/#pre-trained-models

![Wine Recommendation Project_페이지_01](https://user-images.githubusercontent.com/83590357/178478192-72a8b9b0-fa39-4255-802b-e43c326b0e92.png)
![Wine Recommendation Project_페이지_02](https://user-images.githubusercontent.com/83590357/178478214-375460b9-eacb-42c4-920f-c23462a7aa1f.png)
![Wine Recommendation Project_페이지_03](https://user-images.githubusercontent.com/83590357/178478217-130e0699-6c00-44d5-bc98-f66c22442247.png)
![Wine Recommendation Project_페이지_04](https://user-images.githubusercontent.com/83590357/178478220-2d181991-7fd1-49a4-b4a7-006c11abe540.png)
![Wine Recommendation Project_페이지_05](https://user-images.githubusercontent.com/83590357/178478227-51cd76ed-1f0c-4aa0-9194-003527569932.png)
![Wine Recommendation Project_페이지_06](https://user-images.githubusercontent.com/83590357/178478234-166f6427-7667-4db3-90c2-24f19dded21f.png)
![Wine Recommendation Project_페이지_07](https://user-images.githubusercontent.com/83590357/178478238-1508f98d-6f2e-4edd-ade3-66b5735890d3.png)
![Wine Recommendation Project_페이지_08](https://user-images.githubusercontent.com/83590357/178478246-453a46b5-c99b-4845-8a56-b503f3f61898.png)
![Wine Recommendation Project_페이지_09](https://user-images.githubusercontent.com/83590357/178478258-dd3a66c1-54cb-4def-b4b8-c20d1e714d99.png)
![Wine Recommendation Project_페이지_10](https://user-images.githubusercontent.com/83590357/178478285-5085d91d-b9c3-479f-ae84-3dcc4599fdac.png)
![Wine Recommendation Project_페이지_11](https://user-images.githubusercontent.com/83590357/178478317-a4927e19-0e19-41f6-936a-1a83932bcb82.png)
![Wine Recommendation Project_페이지_12](https://user-images.githubusercontent.com/83590357/178478318-964d93fa-a800-4f0a-957a-1aab0e43faac.png)

