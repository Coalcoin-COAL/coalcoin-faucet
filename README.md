# coalcoin-faucet
Coalcoin coin faucet (php) for all coin


В файле index.php указываем логин и пароль от RPC кошелька и если надо то поменять стандартный порт 9982

В файле faucet.php указываем секретный ключ рекапчи, логин, пароль и порт от RPC кошелька. Минимальную и максимальную выплату на кошелек посетителя (переменная $min и $max) и максимальную и минимальную выплату, если он повторно хочет сделать выплату на один и тот-же кошелек (переменная $min_2 и $max_2).
