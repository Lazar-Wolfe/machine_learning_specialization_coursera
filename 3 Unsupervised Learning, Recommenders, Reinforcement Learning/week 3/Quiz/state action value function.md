### 1. Which of the following accurately describes the state-action value function Q(s,a)Q(s,a)Q(s,a)?

- [x] It is the return if you start from state sss, take action aaa (once), then behave optimally after that.
- [ ] It is the return if you start from state sss and repeatedly take action aaa.
- [ ] It is the return if you start from state sss and behave optimally.
- [ ] It is the immediate reward if you start from state sss and take action aaa (once).

Correct

Great!

### 2. You are controlling a robot that has 3 actions: ← (left), → (right) and STOP. From a given state sss, you have computed Q(s, ←) = -10, Q(s, →) = -20, Q(s, STOP) = 0.

What is the optimal action to take in state sss?

- [x] STOP
- [ ] ← (left)
- [ ] → (right)
- [ ] Impossible to tell

Correct

Yes, because this has the greatest value.

### 3.For this problem, γ=0.25\\gamma = 0.25γ=0.25. The diagram below shows the return and the optimal action from each state. Please compute Q(5, ←).

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/3cbf737d-d132-4a1f-8e14-8865ff330e28image3.png?expiry=1660176000000&hmac=Toe2yBVP8oeQ_aOlHK7NBu5uSeU5ROElA_1hC7q_rxc)

- [x] 0.625
- [ ] 0.391
- [ ] 1.25
- [ ] 2.5

Correct

Yes, we get 000 reward in state 5. Then 0∗0.250 * 0.250∗0.25 discounted reward in state 4, since we moved left for our action. Now we behave optimally starting from state 4 onwards. So, we move right to state 5 from state 4 and receive 0∗0.2520 * 0.25^20∗0.252 discounted reward. Finally, we move right in state 5 to state 6 to receive a discounted reward of 40∗0.25340 * 0.25^340∗0.253. Adding these together we get 0.6250.6250.625.