# Papers


#### 5/5/2019
### Domain Adaptation
* A Survey of Domain Adaptation for Neural Machine Translation
* https://www.aclweb.org/anthology/C18-1111

* Domain Adaptation forMultilingual Neural MachineTranslation
* https://www.clubs-project.eu/assets/publications/other/MSc_thesis_AdamVarga.pdf

#### 4/3/2019
### LEARNING DEEP REPRESENTATIONS BY MUTUAL INFORMATION ESTIMATION AND MAXIMIZATION
* https://arxiv.org/pdf/1808.06670.pdf
* https://github.com/rdevon/DIM
* unsupervised learning of representations by maximizing
* mutual information between an input and the output of a deep neural network encoder(Deep InfoMax)

#### 27/2/2019
### Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks
* solve new learning tasks using only a small number of training samples
* https://arxiv.org/pdf/1703.03400.pdf
* https://github.com/cbfinn/maml


#### 26/2/2019
### Mixed-Precision Training for NLP and Speech Recognition with OpenSeq2Seq
* 1. Automatically scale loss to prevent gradients from underflow and overflow during backpropagation. The optimizer inspects gradients at each iteration and scales the loss for the next
iteration to ensure that the values stay within the FP16 range.
* 2. Maintain a FP32 copy of weights to accumulate the gradients after each optimizer step.
* https://arxiv.org/pdf/1805.10387.pdf
* https://github.com/NVIDIA/OpenSeq2Seq

#### 25/2/ 2019
### Simple Recurrent Units for Highly Parallelizable Recurrence
* https://arxiv.org/pdf/1709.02755.pdf
* https://github.com/taolei87/sru

#### 24/2/2019
### Squeeze-and-Excitation Networks
* “Squeeze-and-Excitation” (SE) block, that adaptively recalibrates channel-wise feature responses by explicitly modelling interdependencies between channels
* Squeeze: global distribution of channel responses
* Excitation: gating mechanism to produce chanel-wise weights
* Scale: reweighting feature maps
* http://aclweb.org/anthology/C18-1266
* https://github.com/taki0112/SENet-Tensorflow
#### 23/2/2019 
* deepQuest: A Framework for Neural-based Quality Estimation, 2018, Sheffield
* http://aclweb.org/anthology/C18-1266


## Improvement point of Neural MT 

1. Rare word problem 
      * Jean, S., Cho, K., Memisevic, R., & Bengio, Y. (2014). On using very large target vocabulary for neural machine translation. arXiv preprint arXiv:1412.2007.
      * Luong, M. T., Sutskever, I., Le, Q. V., Vinyals, O., & Zaremba, W. (2014). Addressing the rare word problem in neural machine translation. arXiv preprint arXiv:1410.8206.
2. Monolingual data usage 
      * Sennrich, R., Haddow, B., & Birch, A. (2015). Improving neural machine translation models with monolingual data. arXiv preprint arXiv:1511.06709.
      * Cheng, Y., Xu, W., He, Z., He, W., Wu, H., Sun, M., & Liu, Y. (2016). Semi-supervised learning for neural machine translation. arXiv preprint arXiv:1606.04596.
3. Multiple language translation/multilingual NMT 
      * Dong, D., Wu, H., He, W., Yu, D., & Wang, H. (2015). Multi-Task Learning for Multiple Language Translation. In ACL (1) (pp. 1723–1732).
4. Memory mechanism 
      *  Wang, M., Lu, Z., Li, H., & Liu, Q. (2016). Memory-enhanced decoder for neural machine translation. arXiv preprint arXiv:1606.02003
5. Linguistic integration 
     * Sennrich, R., & Haddow, B. (2016). Linguistic input features improve neural machine translation. arXiv preprint arXiv:1606.02892.
6. Coverage problem 
     * Tu, Z., Lu, Z., Liu, Y., Liu, X., & Li, H. (2016). Modeling coverage for neural machine translation. arXiv preprint arXiv:1601.04811.
7. Training process
     * Shen, S., Cheng, Y., He, Z., He, W., Wu, H., Sun, M., & Liu, Y. (2015). Minimum risk training for neural machine translation. arXiv preprint arXiv:1512.02433.
8. Priori knowledge integration
     * Cohn, T., Hoang, C. D. V., Vymolova, E., Yao, K., Dyer, C., & Haffari, G. (2016). Incorporating structural alignment biases into an attentional neural translation model.
     arXiv preprint arXiv:1601.01085.
9. Multimodal translations
     * Hitschler, J., Schamoni, S., & Riezler, S. (2016). Multimodal pivots for image caption translation. arXiv preprint arXiv:1601.03916.

## NLP
**Awesome NLP**: https://github.com/keon/awesome-nlp
