# KDD-Cup-1999-Intrusion-Detection-Python
KDD cup 1999 is a dataset design to detect network intruders from hacking a web server thus protecting a computer network from unauthorized users, including perhaps insiders.  Although, the dataset operate with the principle of multiclass classification but in practice, it can be said to operate as binary classification where outcomes are chosen between two attack types namely; normal and an attack. The attack include ipsweep, Neptune, satan, buffer overflow, port scanning etc. For easy conveniences, the attack types can be group into four main categories:
•	DOS: denial-of-service, e.g. syn flood;
•	R2L: unauthorized access from a remote machine, e.g. guessing password;
•	U2R:  unauthorized access to local superuser (root) privileges, e.g., various ``buffer overflow'' attacks;
•	Probing: surveillance and other probing, e.g., port scanning.
Owning to the fact that the nature of the dataset is cumbersome, the research attempt to take ten percent of the raw dataset. Firstly, the dataset was split in a ratio of 20:80 called the test and train set. The machine learning algorithm of classification technique was apply to the test and trained set. The type of classification algorithm used is that of Guassian Naïve Bayes algorithm. A model was built from the trained data from which prediction was made.
