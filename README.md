# WebAnalysis_University-Course
This is our project in Web Analysis Course. We used python to make a model which classified sentiment Vietnamese book reviews on an ecommerce website, our feature extraction is TF-IDF and Bag of Words with SVM model.

Our model are structured such as the following image:

![Image of Model](https://raw.githubusercontent.com/anhthuan1999/WebAnalysis_University-Course/master/results/model.PNG) 
<br/>

We used two kernel SVM model: linear and rbf and choose the best one<br/>
The linear model:
![Image of Linear](https://raw.githubusercontent.com/anhthuan1999/WebAnalysis_University-Course/master/results/linear.png) 
<br/>

The rbf model
<br/>
Image of Bag of Words Unigram:
<br/>
![Image of Bag of Words Unigram](https://raw.githubusercontent.com/anhthuan1999/WebAnalysis_University-Course/master/results/unibo.jpg)<br/>
Image of TF-IDF Unigram:
<br/>
![Image of TF-IDF Unigram](https://raw.githubusercontent.com/anhthuan1999/WebAnalysis_University-Course/master/results/unitf.jpg) 
<br/>
Image of Bag of Words Bigram:
<br/>
![Image of Bag of Words Bigram](https://raw.githubusercontent.com/anhthuan1999/WebAnalysis_University-Course/master/results/bibo.jpg)
<br/>
Image of TF-IDF Bigram:
<br/>
![Image of TF-IDF Bigram](https://raw.githubusercontent.com/anhthuan1999/WebAnalysis_University-Course/master/results/bitf.jpg)
<br/>
<br/>
The best model is linear SVM model with F1_Score is 79.44%, C is 100 or 1000. After that, we apply this model with book "Nhà Giả Kim" which has more than 3000 comments and analyze product features

Content Analysis:
<br/><br/>
![Image of Content](https://raw.githubusercontent.com/anhthuan1999/WebAnalysis_University-Course/master/results/content.png) 
<br/>

Quality Analysis:
<br/><br/>
![Image of Quality](https://raw.githubusercontent.com/anhthuan1999/WebAnalysis_University-Course/master/results/quality.png) 
<br/>

Service Analysis:
<br/><br/>
![Image of Service](https://raw.githubusercontent.com/anhthuan1999/WebAnalysis_University-Course/master/results/service.png) 
<br/>
Our project is made by 404NotFound Team:
1. Kim Dang Thi Thu
2. Nguyen Thai Ha
3. Thai Ngo Hoang
4. Thuan Tran Anh
5. Truc Tang Thanh <br/>
If you have any questions, please contact: thuanta17411@st.uel.edu.vn
