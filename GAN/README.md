# Generative Adversarial Nets

생산적 적대 신경망

Generator(생성자)와 Discriminator(구분자)를 경쟁적으로 학습시키는 방법


- Generator는 Fake data를 만들어 Discriminator를 속이는 것
- Discriminator는 Generator가 만든 Fake data와 Real data를 구분하는 것

위 두가지를 학습 시키면 Real data와 구분할 수 없는 Fake data를 얻을 수 있다.

이 과정을 Adversarial Training이라 부른다.