# matlab-programs
Программы на matlab (инженерия)

## Задача функции в matlab и её вызов
```matlab
f = @(x) x.^3 + 15*x - 10
resultY = f(ab)
```

## Построение графиков в matlab
```matlab
figure('Name','Название графика');
plot(u,i,'black','LineWidth',2);
grid on;
xlabel('u, B');
ylabel('i, мА');
```