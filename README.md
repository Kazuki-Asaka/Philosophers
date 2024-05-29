# 課題について
* スレッドを用いて食事する哲学者問題の実装

# プログラムの動かし方
```
./philo number_of_philosophers time_to_die time_to_eat time_to_sleep
./philo number_of_philosophers time_to_die time_to_eat time_to_sleep [number_of_times_each_philosopher_must_eat]
```

* 誰も死なないパターン
```
./philo 3 600 200 200
```

* 誰か死ぬパターン
```
./philo 3 500 200 200
```

* 指定された回数分食べて終了
```
./philo 3 600 200 200 5
```
