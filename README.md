# transfer_learning_lip_ISSCS2021

**Toward Language-independent Lip Reading: A Transfer Learning Approach at ISSCS21**


In this repository are presented the vocabulary of each subset used on our lip reading experiments published in the 15-th International Symposium on Signals, Circuits and Systems.

To deal with a multilingual setup, we have split the well-know datasets, like [LRW](https://www.robots.ox.ac.uk/~vgg/publications/2016/Chung16/chung16.pdf), [LRW-1000](https://arxiv.org/pdf/1810.06990.pdf) and [LRRo](https://doi.org/10.1145/3339825.3394932 ) in two categories based on the prediction difficulty, as follow:
- **hard** subset
- **hard+easy** subset

The vocabulary for each subset (hard and hard+easy) on each individual dataset consists the following words:

**English**
- the easy subset contains a total of 21,001 utterances, and the easy + hard subset contains a total of 49,199 utterances. 
**easy** --- "absolutely", "abuse", "according", "action", "actually", "africa", "benefits", "border", "business", "country", "crime", "europe", "events", "everything", "expected", "football", "foreign", "forward", "happening", "hospital", "human", "immigration", "important", "information", "inside", "islamic", "justice"; **hard** --- "known", "medical", "meeting", "message", "military", ",millions", "operation", "parents", "parliament", "parts", "perhaps", "political", "position", "prices", "response", "schools", "scottish", "secretary", "system", "taking".

**Romanian**
- the easy subset contains a total of 1,087 utterances, and the easy + hard subset contains a total of 5,386 utterances. 
**easy** --- "apararea", "aruncare", "comision", "directioneaza", "dispozitiv", "europa", "filmeaza", "incendiu", "intalnire", "jandarmi", "limita", "lovitura", "masina", "multimedia", "pachetul", "perioada", "pietre", "privat", "protest", "protesteaza", "puterea", "securitate", "siguranta", "supraveghere", "teama", "televiziunea", "trage"; **hard** --- "aceasta", "bucuresti", "cincizeci", "douazeci", "dumneavoastra", "inainte", "inceput", "informatii", "inseamna", "intr-un", "lucrurile", "milioane", "momentul", "niciodata", "probabil", "problema", "referendum", "romana", "romania", "scoala".

**Mandarin**
- the easy subset contains a total of 11,810 utterances, and the easy + hard subset contains a total of 20,606 utterances. 
**easy** --- "bei jing shi jian", "biao zhi", "da xing", "dai biao", "dong bu", "dou", "gei", "guo qu", "meng", "na", "ping tai", "tao", "ti sheng", "ting", "wen ding", "xi jin ping", "xing dong", "ying ji", "yong", "zhao kai", "ai ji", "bao chi", "bo chu", "bu duan", "cai fang", "chi xu"; **hard** --- "dong xi", "gou tong", "hu bei", "ju ban", "meng xiang", "qi wen", ",qiang", "qu nian", "shi liu", "shu ji", "ta men", "tan suo", "tian ran qi", "tui dong", "wem hua", "xin xing", "yi ding", "yi zhong", "zhong fang", "zi you", "zuo chu".

The dispersion of the number of instances for each class is visually presented in the below picture.

![LRM_statistics_git](https://user-images.githubusercontent.com/39959212/112307956-3e26ef00-8caa-11eb-9747-e76433d0ba75.png)

If you make use of this collection, please acknowledge the work of the authors by citing the following publication: Andrei Cosmin Jitaru, Liviu Daniel Ștefan and Bogdan Ionescu. Toward Language-independent Lip Reading: A Transfer Learning Approach. In 15-th International Symposium on Signals, Circuits and Systems (ISSCS21), June 14, 2021, Iași, Romania, IEEE, 4 pages, DOI: NA.
