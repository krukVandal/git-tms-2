# Задача 2:
# Для выполнения задачи использовались команды:
# 1. git checkout/switch -- для изменения ветки
# 2. git branch --all -- для отслеживания ветки
# 3. git log, git status, git commit
# 4. git restore --hard HEAD~1 -- для принудительного удаления последнего коммита в ветке feature
# 5. git reset --soft HEAD~2 -- для слияния двух последних коммитов в ветке develop
# 6. git restore --worktree --source develop --- в ветке experiment для возвращения файлов (readme.md, calculate.py) к состоянию develop
# 7. git rm -- для удаления файлов

# How to use calculator:
1. Run `python calculate.py`
2. Enter the figure name. Available are Circle, Square.
3. Enter the function: Area or Perimeter.
4. Enter figure sizes. Radius for circle, one side for square.
5. Get the answer!

# Math formulas
## Area
- Circle: `S = πR²`
- Rectangle: `S = ab`
- Square: `S = a²`
- Triangle: `S = sqrt(p * (p-a) * (p-b) * (p-c))` where p is semiperimeter

## Perimeter
- Circle: `P = 2πR`
- Rectangle: `P = 2a + 2b`
- Square: `P = 4a`
- Triangle: `P = a + b + c`

