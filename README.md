# CarND-Controls-PID
Self-Driving Car Engineer Nanodegree Program

# PID parameters

The following parameters are used by manual tuning:

```
Kp = 0.1
Ki = 0.001
Kd = 3
```

#  the effect each of the P, I, D components:

1. P component is the proportional gain which computes an output proportional to the cross-track error. 
2. I component is the integral gain which sums up the cross-track error over time which mitigates the bias.
3. D component is the slope of the cross-track error which can predict system behavior and thus improves settling time and stability of the system ([wikipedia](https://en.wikipedia.org/wiki/PID_controller#Derivative_term)).

# A video file is attached.