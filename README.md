# qt_blog-ddos_article
Extremely basic network intrusion detection sytem using machine learning

Note that **we will use only two labels**, thus won't classify exactly the type of attack it is but only try to detect any unusual network activity. We want this little implementation to be as simple as possible. For our little toy-implementation, we will use KDD intrusion dataset detection. 

The KDD training dataset consisting of 10% of the original dataset contains approximately 494,020 single connection vectors and 41 features. Each vector is labeled as either normal or an attack, with exactly one specific attack type. **Deviations from 'normal behavior,' everything that is not 'normal,' are considered attacks.**

The article is featured on https://secjuice.com , an amazing community-driven blog about Information Security.  
[You can find it here](https://www.secjuice.com/deep-learning-cybersecurity/)

You can also find it on our blog https://quantrack.github.io
