# Understanding Temperature TopK and TopP Paramters.

#### Note: Note all the paramters are shared between the models(not all the models have the frequency penality) and json configration and naming schema is different between the models. (top P vs top_P)

### Text Generation Paramters:
#### Max Token generation Length
Token can be word or a few N charaters.
This Parameter sets a limit on the number of tokens that model can generate in response to the prompt
For Instance if the Max token generation length is set to 500, the model will not produce a response that exceeds a response that exceeds 500 tokens

- Temperature
The Temperature Parameter in LLM controls the randomness or creativity in the model responses.
A lower temperature makes the model's response more deterministic and predictable. often sticking closely
to the most likely ouput based on its training.
- Top P
- stop and finish Sequence


## Temperature 
Lower the temperature the values:- shows less randomess will provide straight single answer all the time.
No matter how many times we call them :;- same
```defines the probabity distribution of different words```
you can increase the temperature to attempt to get creative results from the LLM
For tasks requiring high accuracy and reliability, such as factual reporting or techincal explanations a lower temperature is preferred.

for creative task like story telling or poetry pick a high temperature is required.

# Top K
No of the heighest volabulury tokens


# Top P
< 1


Setting a 0 temperature and lvery low top_P is a good approch to get consistent results

## Stop of finish sequence
You can also specify a stop sequence for an LLM.Most Models accept a list of potential stop sequence.

