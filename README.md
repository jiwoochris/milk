# MiLK: Make it like a Human

많은 사람들이 불편해 하는 것.
AI 생성 텍스트가 기계적이고 딱딱한 문체이다. 사람이 쓴 것 같지 않고 어딘가 티가 난다.
따라서 AI가 생성한 텍스트를 인간이 쓴 것처럼 변환해주는 모델이 있으면 좋지 않을까

AI 글 판단기를 하나 개발 -> 점수가 나옴 -> GAN의 Discriminator
Human like LLM -> AI체를 Human체로 바꿔줌 -> GAN의 Generator 역할

근데 이게 Human 데이터가 100개만 있어도 되게하려면 할 수 있을까?
