# myosin_steping_model
The goal of this model is to mimic the behavior of M11 motor clusters of the type designed by the Bryant group. These are motors with a small number of heads per cluster (2-8) that have artificial spectrin-based lever arms and fast-moving Myosin 11 heads. Previous models of uncoordinated stepping have yielded fair results in elucidating the processivity of dimers on single filaments. However here we aim for a more complete picture of motor stepping that can be easily abstracted to any number of heads.

Steps only occur if a single head is bound. Otherwise, the second head serves as an anchor of sorts and prevents the internal power-stroke of the motor head to be converted into the motion of the cluster at large. As we are interested in the long time behavior of these motors we start by assuming that the relaxation of any internal strains (i.e. the powerstroke) is much faster than the biochemical transition rates. This allows us to specify the position of the motor knowing only the previous position and the current biochemical state of all the heads.

A full description of the model including the choices for all parameters can be found in the preprint.
