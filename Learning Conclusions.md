First, I should build my machine learning system quickly and simply, shouldn't over think it and make it complex at start.
After built up my machine learning system, then compare its performance with human-level performance, analize its bias/variance, to optimize it close to Bayers Error as much as possible.

Error Analysis

  Mismatch Data
    If my training set and dev/test set are comes from difference distribution, this may cause to mismatch data error. 
    By comparing train-dev set error with dev set error, I can figure out how big is my mismatch data error. 
    How to address the mismatch data error?
      Do manual error analysis to try to understand the difference between traing set and dev set.
      Make training set more similiar to dev/test set.
      Artificial data synthesis.

Transfer Learning
  Transfer learning is to modify several hidden layers in a learnt model and keep other leant parameter fixed, to learn to do a new task.
  If I want to transfer learning A -> B, I will make sure:
    Data for task A is much more than task B;
    Task A and task B have same input;
    The lower layers' learning result is helpful to learning B.
  We call it a pre-learn to fine-tune process if all layers' parameters are re-learned.
  
Multi-task Learning
  Using one model but have more than one result.
  When will multi-task make sense?
    Trainning on a set of tasks that could benifit from having shared low-level features.
    Amount of data I have usually for each task is similar.
    Can train a big enough network to make good for all tasks.
 
End-to-end Deep Learning
  Instead to divide the task into a pipe-line procedure, end-to-end deep learning using a model to give the output.
  If you have tons of datas, it is a good idea to use end-to-end deep learning.
  
***
# GITHUB ITSELF
### REPOSITORY & PROJECT
Project belongs
      
     
