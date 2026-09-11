# Adversal_Deep_Hedging-_Learning_to_Hedge_without_Price_Process_Modeling
This is a research paper implementation with my own understanding of the paper and putting effort to replicate the given structure provided in the paper 
The following is the link for the research paper that is being implemented 
      :-->https://share.google/QKvsy50IeyD2xSl6u
    
The papers presents a structure that solves two problem 
  1. Generating reliable data (as market data is scarse)
  2. Using adversal learning to hedge and maximize the utility function in a traditional min max approach
the generation is handled by the generator and the hedging is handled by hedger and both are based on Adversal learning methods

Though the implementation is based on the current understanding of the topics.

The entire implementation will be in three stages

  1.Early setup (black scholes , greeks , data operations ,etc)
  
  2.Main highlights Gnerator and Hedger
  
  3.Testing and comparison of the performance of the Hedger

 The early setup consist of data loading i have used old july 2017 nifty50 min by min data for both options and asset (index)
 following are the data sites that i have used for the project
 
   :-->https://www.google.com/goto?url=CAESWwHrOzAVqtSlUU6Ms00PRTaIfiq9RVXF2G2zTBmGyj2x_AGod2rm2tXuTTxY6NtWQD7m255SQzsnXkjIH8vIkGrYhoglDBzBOypi4zeMf0WtbxqN1Jxtt4A7T-c
  
   :-->https://www.google.com/goto?url=CAESYQHrOzAVe-06iTmPHxOO7A4efxhiOcee5inX_stmBbENEsdHoE_3Vmil7qtz25GNDbpghnnOI5huMsn_QVCY2zQoFvbgc20GZ0HfzEK3UiGiBPj3CS00WYZbv5mONWqBd5Y
   
As I am implementing the delta neutral strategy i have taken an option and vary my underlying asset (nifty 50) till the expiary of the option ,since nifty 50 has too many stocks inside it , it would be hard for me to model the cost function with so many stocks and their transaction cost i have made an assumption of zero transaction cost with this aspect .

I have had a resource crunch for building this process this project , change the parameters of generator and the hedger for more data and desired rnn
