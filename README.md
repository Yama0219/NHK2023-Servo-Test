# NHK2023-Servo-Test

* TIM2のTIM_CHANNEL_1とTIM_CHANNEL_2で50Hz，540us~2400usのPWMを出す．
* 2つを向かい合わせで使うので，片方の動きを反転

* targetに角度を入れれば動くはず

```c
#define PWM_MIN 540
#define PWM_MAX 2400
```
で0度と180度になるときのON時間(us)を設定

```c
#define A_OFFSET 0
#define B_OFFSET 50
```
で初期状態の角度を設定

