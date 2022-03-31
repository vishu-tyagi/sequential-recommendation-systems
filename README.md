# Sequential Recommendation Systems Using Stochastic Self- Attention Sequential Model
Repository for Deep Learning Spring 2022 Project: Sequential Recommendation Systems Using Stochastic Self- Attention Sequential Model

Contributors:
1.  Sankalp Apharande, Columbia University, New York, NY 10027 (Email: spa2138@columbia.edu)

2.  Aarushi Jain, Columbia University, New York, NY 10027 (Email: aj3087@columbia.edu)

3.  Vishweshwar Tyagi, Columbia University, New York, NY 10027 (Email: vt2353@columbia.edu)
    
    
    
**Background:**  
     The existing models fail to incorporate dynamic uncertainty in users’ real-life sequential behavior and also fail to incorporate collaborative transitivity. Another limitation of this model is the failure
to capture collaborative transitivity due to dot-product self-attention. Collaborative transitivity can capture the latent similarity between item-item relationships. For example, if a->b and b->c, the dot
product self-attention mechanism will identify the relationship between items (a,b), and (a, c). But, it would fail to realize the relationship between a and
    
**Problem Statement:**  
     The problem statement is: Given a set of users U and items V and their associated interactions in chronological order, our goal is to recommend topN items as potential next item in the sequence
by incorporating the user’s dynamic uncertainty in choices and collaborative transitivity in item interactions.
