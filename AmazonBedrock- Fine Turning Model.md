# AmazonBedrock- Fine Turning Model

Note: Not all the models can be fine tuned
Re-training an FM requires a higher budget 

Instruction-based fine tuning is usually cheaper as computations are less intense and amount of data requried is less

## Steps for Fine Tuning the model.
1.  Adapt a copy of foundational model with your own data.
2.  Fine tune will chnage the weights of the base foundational model.
3.  Training  data must:
     1. Adhere to specific format
     2. Be stored in the Amazon S3
4. ```Provision Throughtput``` or On-demand options for using the model.

