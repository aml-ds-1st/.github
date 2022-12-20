# **AML Data Science 1st**

Powered by [Advacnced Manufacturing Laboratory(AML)](https://amlkorea.com) and 
[`CheoljeongPark`](https://incorpcj.notion.site/C-V-CheolJeong-Park-c27d08f2c3e04c86b832eab54dc70341).<br>
Sponsored by `2022 research mate support project by Chungnam National University (Nov 2022 ~ Jan 2023)`

This project is to analyze time-series effects on Rail Temperature Prediction Model (RTPM) basd on Machine Learning Mehtods. We mainly analyze 

# Analysis of time-series effects on Rail Temperature Prediction Model based on Machine Learning Methods.

## 0. READ ME!

> These codes are for `new AML lab member` studying machine learning and anyone who interested in machine learning prediction for rail temperature.  
>
> We use `python`(<u>_mostly jupyternotebook_</u>) on our code.
> These codes are developed by [`Sung Uk Hong`](https://scholar.google.co.kr/citations?user=xzAMkycAAAAJ&hl=ko&oi=sra), [`CheolJeong Park`]()  and [`Jongwon Yoon`]().  
>
> Raw data(rail temperature and climate data) used on these codes are not provided! (Becacuse of paper issue)<br>
>
> If you need more detailed information or collaborative research, please contact us!  
>
> 
> `Cheol Jeong Park` : **pffiro@gmail.com**  
> `Jongwon Yoon` : **jongwon3498@naver.com**  
> `Chungsu Han` : **cndtn1999@gmail.com**  
> `Kwanghyo Lee` : **rhkdgy1120@gmail.com**  
> `professor Seong J. Cho` : **scho@cnu.ac.kr**  


## 1. Abstract
>
> `Rail temperature` is critical feature at train industry. Thesedays, where air temperature has increased becasue of abnormal climate, train system is suffered by rail temperature. At high rail temperature, the risk of buckling on rail increases and the train operates at slow speed to keep the trian from derailment resulted from buckling. Train industries have monitored rail temperature by directly measuring rail temperature to maintain the rail and train safety. However, it is difficult to measure temperature across the full section of the rail, because of cost or maintenance of measurement system. The train industries now focus on predicting rail temperature.  
> On this study, we developed `rail temperature prediction model` using machine learning with the data provided by the meteorlogical agency. We developed our model by 4 steps as shown below.  
>>
>>1. Data acquisition at measurement system(desigend by AML)
>>2. Data wrangling and analyzing features
>>3. Select machine learning algorithms and evaluate models
>>4. Select the model showing the best performance
>>5. Analyzing features for predictin rail temperature  
>>
> We evaluated our model's performance with r-square and mean absolute error. Our model showed high performance at the whole range of the rail temperature, especially at high rail temperature(over 40℃), compared to reported rail temperature prediction models. We also explains what features are important for rail temperature at different temperature ranges.