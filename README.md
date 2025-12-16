# brics-astronomy-capstone-project
This repository contain my works during the 8 weeks trainng on Data analytics offered by Brics Astronomy and IDIA.

#Objective
--

Even though the Standard Model (SM) of particle physic is very succesfull in describing the interaction of the known fundamental particles like quarks and leptons through force carriers (bosons) like the photon and gluon, it still can’t explain many phenomena of the universe. For example, we don’t yet understand what is the origin of dark matter and dark energy, which together make up more than 95% of the universe. If a new theory beyond the SM is true, it may predict new physics from these dark area. Like the Z′ boson, which are similar to the photon, some theory admit that if they exist they can be used as portal to interact with these dark matter[].

In this project, we use simulated collision data from CERN to try to detect these Z′ bosons using Machine Learning. We train a Random Forest classifier to separate signal events (where Z′ → tt̄ happens) from background Standard Model processes. However, since each event has more than 100+ variables, this bring us to a problem called the "curse of dimensionality" [2], where the model perform worse when there are too many irrelevant or redundant features. So we try to reduce the number of variables by removing unimportant ones using physical reasoning and statistical analysis.

Then we select the best features and train the model, and evaluate if it can really detect the Z′ if the theory is true.
