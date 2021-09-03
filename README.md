## Computational Approach to Measure Empathy and Theory-of-Mind from Written Texts

#### Yoon Kyung Lee*, Inju Lee, Jae Eun Park, Yoonwon Jung, Jiwon Kim, Sowon Hahn**
#### [Human Factors Psychology Lab](https://hfpsych.snu.ac.kr), [Department of Psychology](https://psych.snu.ac.kr), Seoul National University
#### Correspondence: yoonlee78@snu.ac.kr*, swhahn@snu.ac.kr**

#### Papers

1. CogSci 2021 : [link](https://psyarxiv.com/mpn3w/) <br>

Cite: Lee, YK., Jung, YW., Lee, I., Park, JE., & Hahn, S. (2021). Building a Psychological Ground Truth Dataset with Empathy and Theory-of-Mind During the COVID-19 Pandemic. Cognitive Science Society (CogSci) 2021.

2. ToM Diary + BERT : [link](https://arxiv.org/pdf/2108.11810.pdf) <br>

Cite: Lee, Y. K., Lee, I., Park, J. E., Jung, Y., Kim, J., & Hahn, S. (2021). A Computational Approach to Measure Empathy and Theory-of-Mind from Written Texts. arXiv preprint arXiv:2108.11810.



>>

## Data and Label Description
<br>

<img src = "./figure_ToM_diary.png" width = 500/>

<br>

<br>

- There were four levels: level 0, 1, 2, 3
- Level 0 : no mention of other's presense.
- Level 1 : mentions others' behaviors only.
- Level 2 : mentions other's mental state but refuse or fail to take perspective of them.
- Level 3 : mentions other's mental state and take perspective of them.
- Each sentence was annotated by psychology major students and was reviewed by psychology experts (graduate students)

<br>

## Example

	sent,tom_level
	무작정 회화 학원에 나가 말하는 연습을 하기 시작한 게 벌써 3개월이나 지났다.,0
	며칠 전 친구들과 배달을 시키면서 처음 먹어보는 메뉴를 골랐는데 생각보다 맛이 없었다. ,1
	마스크를 안 썼으면 몸을 사리기라도 해야 하는데 꼭 그런 사람들이 지하철에서 진상 짓을 하고 본인이 진상인지도 몰라서 너무 짜증난다. ,2
	휴학하고 나는 밖에는 자주 나가지 못하지만 집에서 쉬어 좋았는데, 비대면 수업을 듣는 다른 친구들은 평소보다 더한 과제 양에 지친 듯하였다. ,3

<br>

## File Description <br>

	sent : sentence <br>
	tom level: Theory of Mind level annotated to each sentence. <br>
<br>

License: CC-BY-NC-SA 4.0

<br>

Test data used for model inference is at ```/data```. <br>

Train data are available to only researchers from verified institutions due to privacy concerns (e.g., mental health and personal history) <br>

Contact: <br>
snuhahnlab@gmail.com <br>
Human Factors Psychology Laboratory, <br>
Seoul National University, Korea 

### Acknowledgement

This is part of K-Data Agency (한국데이터진흥원) Data Voucher Project (데이터바우처사업). We thank DeepNatural.AI for helping data collection and processing.
We also thank annotators for their help. 
