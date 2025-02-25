# TailGAN-Project

All of the project is based on the paper, 
Cont, Rama, et al. "Tail-gan: Learning to simulate tail risk scenarios." arXiv preprint arXiv:2203.01664 (2022).

This project is conducted during winter internship in FINX Lab, Hanyang University.

Dataset_real is synthetic data with 5 distributions.
TailGAN_Scorefunc is visualized score function which can check the joint elicitability of VaR and ES.
Tailgna is the main file of tail gan training. You can check strategies, discriminator, generator, loss function, etc.
Model_Evaluation is the file for evaluate the distribution of fake dataset. Unlike the real paper, I focused on implemantation of tail gan, so conducted the evlauation process to check how well the fake data follows the distribution of the real data.

Fake dataset is what I make from the tail gan. And model evaluation is conducted with "final_fake_data_epoch_2017_3000"

PDF file will help you understand the project and the code.
This code may have a lot to complement. Modification and pointing out of the code are welcome.
