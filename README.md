# Quantitative Finance Implementations

This repository contains a collection of quantitative implementations in the area of derivative pricing and risk modeling — including Monte Carlo simulations, 
finite difference (PDE) solvers, and Greeks estimation (Delta, Vega) with variance reduction techniques.

I genuinely believe that AI is transforming quantitative finance. If we think it won’t, we risk being left behind. 
AI is making model building more democratic — anyone can create complex implementations almost instantly. 

The true differentiating factor will be who can explain, interpret, and truly understand what’s being built.
Everything here has been created with the support of AI, but reviewed, refined, and annotated by me. 

If it’s here, it’s because I’ve worked through it carefully and understood it in depth.

## TO DO

- Check the Monte Carlo engine, in n_steps=1 gives you 2 values (t_0 - zeros and t_1) should it give you just t_1 ?
- Noticing that a lot of code could be reuse...better to live the code in the ipynb to make it easier for people to understand or put the code in a code base and call the functions in the notebook ? It's like ipynb should be used for Showing the results only or the code as well ? 
    - It might be good to have both ? i.e. Notebook that explain the code, One that explain the results (more theoretical) and the code base as well ?
    