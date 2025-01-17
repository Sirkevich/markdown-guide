Войти в систему под своей учётной записью.\
\
\
![Зображення](media/image1.png){width="2.5678357392825895in"
height="0.5770417760279966in"}

\*Поменять пароль своей учётной записи Изучить основные параметры
команды. Какой системный файл она изменяет\*?\
![Зображення](media/image2.png){width="3.154818460192476in"
height="1.280411198600175in"}\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
*\
\
**passwd** змінює паролі до облікових записів користувачів. Простий
користувач може змінити пароль тільки собі, **root** може змінювати
паролі усім.Використовує **Pluggable Authentication Modules** для
аутентифікації та зміни паролів користувачів.\
\
**/etc/passwd** - зберігає інформацію про облікові записи користувачів.\
**/etc/shadow** - зберігає інформацію про зашифровані паролі облікових
записів користувачів. (Цей файл оновлюється після зміни паролю).\
**/etc/pam.d/passwd** - PAM-конфігурація для passwd.*

Определите в каком каталоге вы находитесь\
\
\
![Зображення](media/image3.png){width="2.7156878827646542in"
height="0.667011154855643in"}

Освоить справочную систему Linux, а также команды man и info. Получить
справку по рассмотренным ранее командам, определить и описать два любых
ключа для данных команд. Привести примеры.\
\
***passwd -n** - встановлює мінімальну кількість днів перед зміною
паролю. В прикладі встановюю 30 днів до зміни паролю користувачу sirko*\
\
\
\
![Зображення](media/image4.png){width="4.930195756780402in"
height="0.6903674540682415in"}

***passwd -S** - інформація про пароль користувача.*

![Зображення](media/image5.png){width="4.347222222222222in"
height="0.75in"}

***P** - пароль встановлений*

***04/02/2023** - дата останньої зміни паролю*

***30** - мінімальний термін дії пароля*

***99999** - максимальний термін дії пароля*

***7** - сповіщення про необхідність зміни пароля будуть виводитись за 7
днів до закінчення терміну дії пароля.*

***-1** - пароль не буде заблоковано після закінчення терміну дії.*

***info -k** - дозволяє знайти заданий рядок у всіх індексах довідкових
посібників.*

*У даному прикладі шукаю слово linux.*

![Зображення](media/image6.jpeg){width="6.26375in"
height="2.7007338145231845in"}

***info -o** - дозволяє вивести результат команди у файл.*

*У даному прикладі у файл результат команди info pwd.*

![Зображення](media/image7.png){width="5.183333333333334in"
height="4.7in"}

Изучить команды more и less с помощью справочной системы. С помощью
команд просмотреть содержимое файлов .bash\*.

> ***More** -- це примітивний фільтр перегляду тексту. **Less** --- це
> програма, схожа на more , але вона має набагато більше функцій та
> навігаційне меню. Вона не має читати весь вхідний файл перед запуском,
> тому з великими вхідними файлами він запускається швидше, ніж текстові
> редактори.*
>
> ![Рисунок 1](media/image8.png){width="5.490277777777778in"
> height="2.0520833333333335in"}
>
> ![Рисунок 2](media/image9.png){width="5.740384951881015in"
> height="1.5731364829396326in"}
>
> ![Рисунок 3](media/image10.png){width="5.7125in"
> height="2.3826082677165354in"}

\* Вывести содержимое домашнего каталога с помощью команды ls,
определить его файлы и каталоги. Подсказка: с помощью справочной системы
ознакомьтесь с командой ls.\
\
![Рисунок 4](media/image11.png){width="4.5472222222222225in"
height="0.921738845144357in"}

С помощью какой команды можно определить тип файла (например, текстовый
или бинарный)? Привести пример\
\
*Тип файлу можна визначити за допомогою команди **file**.* *Ця команда
використовується для визначення типу файлу на основі його вмісту та
виводить інформацію про цей файл, включаючи його назву та тип. Якщо цей
файл є бінарним, то у виводі буде згадуватися фраза **\"executable\"**\
\
*![Рисунок 6](media/image12.png){width="6.268055555555556in"
height="0.6291666666666667in"}*\
\
Якщо цей файл є текстовим, то у виводі буде згадуватися фраза
**\"text\".\
**\
*![Рисунок 7](media/image13.png){width="3.1566918197725284in"
height="0.5521609798775153in"}

Овладеть навыками навигации по файловой системе при помощи относительных
и абсолютных путей. Как можно вернуться в домашний каталог из любого
места в файловой системе?\
**\$cd\
\$cd \~\
\$cd \$HOME**

> **\$cd /home/user_name**

Ознакомиться с различными ключами команды **ls**. Привести примеры
распечатки каталогов с использованием различных ключей. Объяснить
выведенную на терминал информацию с помощью ключей **--l** и **-a**.\
\
\
*Команда **\"ls -с -lt\"** відображає відсортовані файли по даті
останнього редагування.*\
\
\
![Зображення](media/image14.png){width="3.680825678040245in"
height="0.5594860017497812in"}\
\
\
\
\
\
\
\
\
\
*Команда **\"ls -i\"** виводить індексні*
![Зображення](media/image15.png){width="2.9968667979002626in"
height="0.43388998250218724in"}*номери кожного файлу.*\
\
\
\
\
\
\
\
\
*\
\
Команда **\"ls -alhS\"** відображатиме детальну інформацію про всі файли
та директорії, включаючи приховані, в зрозумілому для людини форматі та
сортуватиме їх за розміром у порядку спадання.\
*![Зображення](media/image16.png){width="6.263888888888889in"
height="2.9671062992125985in"}\
*Команда **\"ls -l\"** виводить список файлів і директорій в поточній
робочій директорії з докладним описом кожного з них.*

![Зображення](media/image17.png){width="4.179186351706036in"
height="0.6376498250218723in"}\
\
\
\
\
\
\
\
\
\
\
\
***Перший ствопець** показує тип файлу, в даному випадку\
**-** простий файл\
**d** - директорія\
**Cтовпці 2-4** показують права на файл чи директорію для власника,
групи та інших користувачів, в даному випадку\
**rw-rw-r---** читання,запис для власника, групи і читання для іншіх на
файл.\
**rwxrwxrwx** - читання,запис,виконання для всіх на папку та те, що в
ній.*

***5 стовпець** показує кількість посилань на файл або директорію (на
прикладі 1 для файлу, 2 для директорії).*

***6,7 стовпці** показують власника та групу (власник та група sirko).*

***8 стовпець** показує розмір файлу в байтах (13 для файлу, 4096 для
диреторії)*

***9 стовпець** показує дату та час останньої зміни файлу або
директорії.\
\
команда **\"ls -a\"** виводить список файлів і директорій у поточній
робочій* ![Зображення](media/image18.png){width="7.02953302712161in"
height="0.2733716097987752in"}директорії, включаючи приховані файли та
директорії

 Выполнить следующую последовательность операций:

создать в домашнем каталоге подкаталог;\
\
\
![Зображення](media/image19.png){width="3.0in"
height="0.8215277777777777in"}

в этом подкаталоге создать файл, содержащий информацию о каталогах,
находящихся в корневом каталоге (используя операции перенаправления
ввода-вывода);\
\
![Зображення](media/image20.png){width="5.000485564304462in"
height="1.050330271216098in"}

просмотреть созданный файл;\
\
\
![Зображення](media/image21.png){width="3.979861111111111in"
height="2.966666666666667in"}

скопировать созданный файл в домашний каталог используя относительную и
абсолютную адресацию.\
\
![Зображення](media/image22.png){width="5.040191382327209in"
height="1.0739391951006125in"}\
\
\
\
\
\
![Зображення](media/image23.png){width="5.040191382327209in"
height="0.19583661417322834in"}

удалить созданный ранее подкаталог с файлом с запросом на удаление;\
\
![Зображення](media/image24.png){width="5.078201006124234in"
height="1.391694006999125in"}

удалить файл, скопированный в домашний каталог\
\
\
![Зображення](media/image25.png){width="5.078201006124234in"
height="1.7340201224846894in"}

Определить, какие разделы смонтированы в системе, а также типы этих
разделов.

![Зображення](media/image26.png){width="5.549305555555556in"
height="1.2666666666666666in"}

\*Перенаправить вывод предыдущей команды в файл. Показать результат\
![Зображення](media/image27.png){width="6.263888888888889in"
height="1.9898118985126858in"}

Записать в файл строку "Hello World!"\
![Зображення](media/image28.png){width="5.539379921259843in"
height="0.7962150043744531in"}

Выполнить следующую последовательность операций:

создать в домашнем каталоге подкаталог;\
\
\
![Зображення](media/image29.png){width="2.941935695538058in"
height="0.8133005249343832in"}

в этом подкаталоге создать файл;\
\
![Зображення](media/image30.png){width="3.166083770778653in"
height="0.9273447069116361in"}

Запретить запись в этот файл для всех;\
![Зображення](media/image31.png){width="5.180555555555555in"
height="0.3055555555555556in"}

Показать изменения;\
\
![Зображення](media/image32.png){width="4.653762029746281in"
height="0.8058956692913386in"}

Разрешить запись в файл всем;\
\
\
![Зображення](media/image33.png){width="3.95625in"
height="0.7340277777777777in"}

\*Произвести все эти изменения для папки и файла вместе (1 коммандой)\
\
\
![Зображення](media/image34.png){width="3.4775535870516188in"
height="0.7614512248468941in"}

Показать изменения;\
\
\
![Зображення](media/image35.png){width="4.79870406824147in"
height="0.840326990376203in"}

Сделать файл исполняемым\
\
\
![Зображення](media/image36.png){width="4.229420384951881in"
height="0.759896106736658in"}

Выведите все сервисы запущенные на ОС (используйте systemctl)
перенаправьте вывод в
файл![Зображення](media/image37.png){width="7.009010279965004in"
height="3.4453576115485562in"}

Выберите один сервис и покажите его статус\
![Зображення](media/image38.png){width="5.925in"
height="2.9916666666666667in"}

![Зображення](media/image39.png){width="6.263888888888889in"
height="4.262564523184602in"} Посмотрите логи выбранного вами сервиса

Посмотрите unit-файл выбранного вами сервиса\
![Зображення](media/image40.png){width="6.263888888888889in"
height="4.381686351706037in"}
