![PROJECT_PHOTO](https://www.ionline.by/promo/logo/git-logo.png)

# MARLIN_1.1.9_ANYCUBIC_4MAX_Dark_Sarmat_MOD
Прошивка Marlin 1.1.9 для 3D принтера Anycubic 4Max адаптированная для работы с тихими драйверами шаговых двигателей TMC2208. 

![DSMOD_PHOTO](https://static.ionline.by/2019/03/IONLINE.BY-4MAX-INSTALL-TMC2208_PART3-0010-640x480.jpg)

Структура репозитория:

Каталог VARIANT01/SRC Содержит исходники прошивки со следующим функционалом:

	- Каталог MARLIN_1.1.9_4MAX_ENG — содержит в себе исходники прошивки marlin 1.1.9 доработанные мной. Версия меню принтера на английском языке. Поддержка Linear Advanced Включена, но не активна. Включить ее вы можете через меню принтера либо в слайсере Cura.
	- Каталог MARLIN_1.1.9_4MAX_RU —  содержит в себе исходники прошивки marlin 1.1.9 доработанные мной. Версия меню принтера на английском языке. Поддержка Linear Advanced Включена, но не активна. Включить ее вы можете через меню принтера либо в слайсере Cura.
	- Каталог MARLIN_1.1.9_4MAX_ENG_NO_LA — содержит в себе исходники прошивки marlin 1.1.9 доработанные мной. Версия меню принтера на английском языке. Поддержка Linear Advanced Отключена полностью.
	- Каталог MARLIN_1.1.9_4MAX_RU_NO_LA — содержит в себе исходники прошивки marlin 1.1.9 доработанные мной. Версия меню принтера на английском языке. Поддержка Linear Advanced Отключена полностью.
	
Каталог VARIANT01/RELEASES содержит релизы прошивки в разлочных форматах
	Каталог VARIANT01/RELEASES/ARHIVES содержит архивы с исходниаками прошивки следующей структуры:
	
	- SRC_MARLIN_1.1.9_4MAX_ENG_NO_LA_V1.0.zip содержит в себе исходники прошивки marlin 1.1.9 доработанные мной. Версия меню принтера на английском языке. Поддержка Linear Advanced Отключена полностью.
	- SRC_MARLIN_1.1.9_4MAX_ENG_V1.0.zip содержит в себе исходники прошивки marlin 1.1.9 доработанные мной. Версия меню принтера на английском языке. Поддержка Linear Advanced Включена, но не активна. Включить ее вы можете через меню принтера либо в слайсере Cura.
	- SRC_MARLIN_1.1.9_4MAX_RU_NO_LA_V1.0.zip содержит в себе исходники прошивки marlin 1.1.9 доработанные мной. Версия меню принтера на английском языке. Поддержка Linear Advanced Отключена полностью.
	- SRC_MARLIN_1.1.9_4MAX_RU_V1.0.zip содержит в себе исходники прошивки marlin 1.1.9 доработанные мной. Версия меню принтера на английском языке. Поддержка Linear Advanced Включена, но не активна. Включить ее вы можете через меню принтера либо в слайсере Cura.

	Каталог VARIANT01/RELEASES/HEX содержит готовые и скомпилированне прошивки, которые можно заливать с помощью Cura. Содержи следующие варианты прошивки:
	
	- MARLIN_1.1.9_4MAX_ENG.hex прошивка marlin 1.1.9 Dark_Sarmat MOD Версия меню принтера на английском языке. Поддержка Linear Advanced Включена, но не активна. Включить ее вы можете через меню принтера либо в слайсере Cura.
	- MARLIN_1.1.9_4MAX_ENG_NO_LA.hex прошивка marlin 1.1.9 Dark_Sarmat MOD Версия меню принтера на английском языке. Поддержка Linear Advanced Отключена полностью.
	- MARLIN_1.1.9_4MAX_RU.hex прошивка marlin 1.1.9 Dark_Sarmat MOD Версия меню принтера на английском языке. Поддержка Linear Advanced Включена, но не активна. Включить ее вы можете через меню принтера либо в слайсере Cura.
	- MARLIN_1.1.9_4MAX_RU_NO_LA.hex прошивка marlin 1.1.9 Dark_Sarmat MOD Версия меню принтера на английском языке. Поддержка Linear Advanced Отключена полностью.
	
Обновление от 12 января 2020 года

Полностью решена проблема с Linear Advanced путем добавления поддержки драйверов шаговых двигателей TMC2209. В связи с этим отпадает необходимость в большой вариативности прошивок. Новые версии прошивок размещены в каталоге VARIANT02

Каталог VARIANT_02/RELEASES содержит релизы прошивки в разлочных форматах
	Каталог VARIANT_02/RELEASES/ARHIVES содержит архивы с исходниаками прошивки следующей структуры:
	
	- MARLIN_1.1.9_4MAX_EN_V2_TMC220X.zip содержит в себе исходники прошивки marlin 1.1.9 доработанные мной. Версия меню принтера на английском языке. 
	- MARLIN_1.1.9_4MAX_RU_V2_TMC220X.zip содержит в себе исходники прошивки marlin 1.1.9 доработанные мной. Версия меню принтера на русском языке языке.
	
	Каталог VARIANT_02/RELEASES/HEX содержит готовые и скомпилированне прошивки, которые можно заливать с помощью Cura. Содержи следующие варианты прошивки:
	
	- MARLIN_1.1.9_4MAX_EN_V2_TMC220X.hex  версия с меню принтера на английском языке
	- MARLIN_1.1.9_4MAX_RU_V2_TMC220X.hex  версия с меню принтера на русском языке
	
Подробности об изменениях в прошивке VARIANT_02 вы можете прочитать тут: https://www.ionline.by/diy/3d-pechat/anycubic-4max/dnevnik-3d-pechatnika-proshivka-marlin-1-1-9-variant-2-dlya-3d-printera-anycubic-4max-23-01-2020/

Инструкция по установке прошивки с помощью Arduino IDE размещена тут: https://www.ionline.by/diy/3d-pechat/obshhaya-informaciya/ustanavlivaem-proshivku-marlin-na-3d-printer-s-pomoshhyu-arduino-ide-20-01-2020/

Инструкция по прошивке с помошью слайсера Cura вот тут:
https://www.ionline.by/diy/3d-pechat/obshhaya-informaciya/ustanavlivaem-proshivku-marlin-na-3d-printer-s-pomoshhyu-slajsera-cura-ili-chto-delat-s-hex-fajlom-21-01-2020/


Старые, но не менее актуальные материалы:
Информация по установке и настройке драйверов TMC2208 на 3Д принтер Anycubic 4Max вы можете получить в статье "Дневник 3Д печатника. Устанавливаем тихие драйверы TMC2208. Часть 1. Постановка задачи и электрика" перейдя по ссылке: https://www.ionline.by/diy/3d-pechat/anycubic-4max/dnevnik-3d-pechatnika-ustanavlivaem-tixie-drajvery-tmc2208-chast-1-postanovka-zadachi-i-elektrika-25-03-2019/

Информацию по установке прошивки на 3Д принтер Anycubic 4Max вы можете получить в статье "Дневник 3Д печатника. Устанавливаем тихие драйверы TMC2208. Часть 2. Прошивка Anycubic 4max" перейдя по ссылке: https://www.ionline.by/diy/3d-pechat/anycubic-4max/dnevnik-3d-pechatnika-ustanavlivaem-tixie-drajvery-tmc2208-chast-2-proshivka-anycubic-4max-28-03-2019/

Информацию по решению проблем с Linear Advanced и драйверами TMC2208 вы можете получить в статье "Дневник 3Д печатника. Устанавливаем тихие драйверы TMC2208. Часть 3. Решение проблем с Linear Advanced" перейдя по ссылке: https://www.ionline.by/diy/3d-pechat/anycubic-4max/dnevnik-3d-pechatnika-ustanavlivaem-tixie-drajvery-tmc2208-chast-3-reshenie-problem-s-linear-advanced-29-03-2019/

Для тех кто не хочет заморачиваться, создана страница с актуальными релизами прошивки. Она доступна по ссылке: https://github.com/Dark-Sarmat/MARLIN_1.1.9_ANYCUBIC_4MAX_Dark_Sarmat_MOD/releases/
