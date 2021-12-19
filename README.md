
# practical aspects of recommendar systems

There are lots of resources that explain how recommendar system works.
Most of them follow the same outline, at first they explain what content based
filtering, second they explain what colloborative filtering is, followed by
brief explaination about matrix factorization and few deep learning models.

But in general these resources don't clearly explain some practical aspects.

1. When most users are not logged in, is content similarity only option?
2. In case of new items, is content similarity only option?
3. What can be done when you don't have resources to train model online?
4. For deep learning based matrix factorization models do i have to retrain model
   when new user/item is added (because dimension of embedding layer has increased).
5. How do i know if the recommendar system is working?

This repo is currently work in progress, but in the end it will host series of notebooks that answers the questions mentioned above.
