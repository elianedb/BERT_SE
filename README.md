# BERT_SE

BERT_SE is a BERT model trained on a textual dataset in the area of software engineering.

BERT_SE passou por um processo de ajuste-fino, utilizando os algoritmos disponibilizados pelos autores do BERT (Devlin, et al., 2019). O dataset utilizado no ajuste-fino, denominado corp_SE, é composto por textos obtidos a partir de problemas e requisitos de usuário do Stackoverflow. Além disso, compóe o dataset, requisitos de software obtained from open-source projects & a textual corpus of 319.026 requirements from 16 large open-source projects in 9 repositories (Apache, Appcelerator, DuraSpace, Atlassian, Moodle, Lsstcorp, Mulesoft, Spring and Talendforge) (Choetkiertikul et al., 2018) and from others 22 open-source datasets (Dalpiaz, 2018).

Therefore, the corp_SE is composed of 456.500 texts, in this paper called sentences. Each sentence has an average length of 61 words. The vocabulary generated by the corp_SE is composed of 1.179.501 words.

It results and details of the evaluation are in the paper. 


References:

[1] Devlin, Jacob, Ming-Wei Chang, Kenton Lee, and Kristina Toutanova. "Bert: Pre-training of deep bidirectional transformers for language understanding." arXiv preprint arXiv:1810.04805 (2018).

[2] M. Choetkiertikul, HK Dam, T. Tran, TTM Pham, A. Ghose e T. Menzies, "A deep learning model for estimating story points.", IEEE Trans. Softw. Eng. Vol. PP, não. 99, p. 1, 2018.

