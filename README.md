# gradient_assisted_calibration_abm
Code for paper "Gradient-assisted calibration for financial agent-based models", 
which appeared in the Proceedings of the Fourth International Conference on AI in Finance. In this paper, we consider how agent-based models can be constructed in a differentiable manner, and how the differentiability of a differentiable agent-based model might be useful for accelerating certain (although not all) parameter inference procedures. See the <a href="https://m.youtube.com/watch?v=ria0aKWztGE">INET Oxford YouTube Channel for a recording of a talk</a> I gave about this paper.

# Running the code
To run this code, use python 3.10 and issue
```
python3.10 -m pip install blackbirds==1.2 jupyter==1.0.0 scienceplots==2.1.0 pygtc==0.4.1 tensorflow==2.14.0
```

# Citation
```
@inproceedings{dyer2023gradient,
  title={Gradient-assisted calibration for financial agent-based models},
  author={Dyer, Joel and Quera-Bofarull, Arnau and Chopra, Ayush and Farmer, J Doyne and Calinescu, Anisoara and Wooldridge, Michael},
  booktitle={Proceedings of the Fourth ACM International Conference on AI in Finance},
  pages={288--296},
  year={2023}
}
```
