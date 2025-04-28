# Stock-Price_prediction-Using-LSTM-and-Sentiment-Analysis
Through  this  project  we  will  be  trying  to  predict  the  stock  price  for  the  upcoming  few  days  after  feeding  in  the  historical  data  and  also  headlines  of  a  particular  stock  and  do  sentiment  analysis  on  it.  Mainly  we  will  be  using  LSTM  which  is  an  advanced  form  of  RNN,  one  of  the  most  important  aspect  of  deep  learning.
Our  main  objective  through  this  project  is  to:
Build  a  model  to  predict  future  stock  prices  using  efficient  Deep  Learning  models  like  LSTM
Next  we  use  sentimental  analysis  to  get  analyse  the  sentiments  of  the  market  
We  try  to  combine  the  above  two  results  into  one  model  that  can  better  predict  the  stock  prices  that  each  one  of  them  along
We  then  try  to  optimize  the  whole  model  try  out  the  latest  models  like  transform  neural  networks.

Dataset:
  historic_prices.pkl : Historic Prices of the stocks analysed.
  Custom.pkl, custom_intel.pkl, custom_cisco.pkl: Headlines mined, whose code is in the files mentioned in later section.
  Msft_senti.pkl, intel_senti.pkl, cisco_senti,pkl: Sentiment Analysis results stored in this dataset.
  Msft_with_time.pkl, intel_with_time_pkl, cisco_with_time.pkl: Sentiment analysis with time stamps.
  Msft_importable.pkl, intel_importable.pkl, cisco_importable.pkl: Combining the dataset with historical data.

Note: The data mining process took approximately 4–8 hours for the preparation of the dataset (on an RTX 2060 GPU with an Intel i5 10th Gen CPU). Please keep in mind that a similar duration will be required if you plan to regenerate it. Additionally, this was developed using Anaconda with Python 3.10, which may cause compatibility issues if run on Google Colab, as Colab typically uses Python 3.6.

There are are total of 6 python notebooks:
Data Mining: MSFT_DATA_MINING.ipynb, INTEL_DATA_MINING.ipynb, CISCO_DATA_MINING.ipynb
Modelling: MSFT.ipynb, Intel.ipynb, CISCO.ipynb

Main Python Libraries Used:
Below listed are the main python libraries we used for this project.
Quandl: To get stock price data from NASDAQ 
Pandas: For creating, saving and loading Data Frames and much more.
NumPy: For improving computational efficiency
Matplotlib and Seaborn: For visualizing the results into charts and graphs
NLTK: For sentiment analysis using lexicon method
Requests: Requesting data to server from a url
BeautifulSoup: For pulling data out of HTML pages 
Urllib: Used along with BeautifulSoup to mine data from webpages
Tensorflow: Mainly used Keras for modelling LSTM 
Sklearn: For metrics and performance. Also used for normalization using  MinMax Scaling
