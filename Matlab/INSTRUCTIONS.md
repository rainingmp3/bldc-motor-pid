
## EN

The project was created on Matlab version R2020b

In order to open the work, you need to run the .mlproj file, which will open the project folder in Matlab.
The first step is to run the Constants.m file (PID folder) so that they are loaded into the project's Worskapce. After that, run the PID.slx file. The finished model will open in Simulink and to compile it, press CTRL+T, now if you click on the Scope blocks, all results will be available.

It is also possible to run the genetic algorithm independently, to do this, run the file gapid.m (Genetic Algorithm folder), where you can also change the number of generations or the number of populations of one generation to speed up the process. When the algorithm finishes, enter x in the Command Window to get the coefficients of the best generated PID. RUNNING THE GENETIC ALGORITHM WILL REMOVE ALL CONSTANTS FROM THE WORKSPACE, SO YOU MUST RENEW THE FILE Constants.m

## UA

Проект створений на версії Матлабу R2020b

Для того, щоб відкрити роботу треба запустити файл .mlproj, пілся чого відкриється папка проекту в Матлабі.
Першим чином треба запустити файл Constants.m (папка PID), щоб вони завантажились в Worskapce проекту. Після цього треба запустити  файл PID.slx. Відкриється готова модель в Сімулінку і для її компіляції треба нажати СTRL+T, тепер якщо нажимати на блоки Scope будуть доступні всі результати. 

Також є можливість самостійно запустити генетичний алгоритм, для цього треба запускати файл gapid.m (папка Genetic Algorithm), в ньому ж можна змінити кількість генерацій, або кількість популяції одної генерації для пришвидшення процесу. Як алгоритм завершиться в Командне Вікно треба ввести  x для отримання коефіцієнтів найкращого ПІД, що було згенеровано. ЯКЩО ЗАПУСТИТИ ГЕНЕТИЧНИЙ АЛГОРИТМ, ТО ВИДАЛЯТЬСЯ ВСІ КОНСТАНТИ З WORKSPACE'у, ТОМУ ТРЕБА БУДЕ ЗНОВУ ЗАПУСТИТИ ФАЙЛ Constants.m