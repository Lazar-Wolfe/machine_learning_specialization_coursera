### 1. The Lunar Lander is a continuous state Markov Decision Process (MDP) because:

- [x] The state contains numbers such as position and velocity that are continuous valued.
- [ ] The reward contains numbers that are continuous valued
- [ ] The state has multiple numbers rather than only a single number (such as position in the xxx-direction)
- [ ] The state-action value Q(s,a)Q(s,a)Q(s,a) function outputs continuous valued numbers

Correct

That’s right!

### 2. In the learning algorithm described in the videos, we repeatedly create an artificial training set to which we apply supervised learning where the input x=(s,a)x = (s,a)x=(s,a) and the target, constructed using Bellman’s equations, is y = _____?
- [ ] y=max⁡a′Q(s′,a′)y=\\max\\limits_{a'} Q(s',a')y=a′max​Q(s′,a′) where s′s's′ is the state you get to after taking action aaa in state sss
- [ ] y=R(s′)y=R(s')y=R(s′) where s′s's′ is the state you get to after taking action aaa in state sss
- [x] y=R(s)+γmax⁡a′Q(s′,a′)y=R(s) + \\gamma \\max\\limits_{a'} Q(s',a')y=R(s)+γa′max​Q(s′,a′) where s′s's′ is the state you get to after taking action aaa in state sss
- [ ] y=R(s)

Correct

### 3. You have reached the final practice quiz of this class! What does that mean? (Please check all the answers, because all of them are correct!)
The DeepLearning.AI and Stanford Online teams would like to give you a round of applause!

Correct

Andrew sends his heartfelt congratulations to you!

Correct

You deserve to celebrate!

Correct

What an accomplishment -- you made it!

Correct