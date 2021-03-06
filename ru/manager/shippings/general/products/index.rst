Параметры доставки товара
-------------------------

Для более точного расчёта стоимости доставки необходимо настроить "Параметры доставки" товаров.

.. contents::
    :local: 
    :depth: 2

Доступные параметры доставки для товара
=======================================

.. list-table::
    :header-rows: 1
    :stub-columns: 1
    :widths: 10 30

    *   -   Параметр
        -   Описание

    *   -   Вес
        -   Используется для расчёта стоимости доставки.

            Товары с нулевым весом доставляются как товары, имеющие минимальный возможный ненулевой вес

            Для изменения единиц измерения веса пройдите:

            ``Панель администратора → Верхнее меню → Настройки → Общие``

            .. fancybox:: img/shippings_043.png
                :alt: Методы доставки

    *   -   Бесплатно

        -   Данный товар не будет учтён при расчёте стоимости. Если в заказе все товары будут иметь данную настройку, то доставка будет бесплатной.

    *   -   Стоимость доставки

        -   Стоимость доставки данного товара в основной валюте магазина. Данная стоимость будет добавлена к общей стоимости доставки.

    *   -   Количество штук в коробке

        -   Используйте это поле, чтобы задать минимальное и максимальное количество штук товара, которое может быть доставлено в одной коробке. 

            Введите ненулевое значение и задайте размеры коробки ниже.

            .. note::

                Универсальное значение для единичного товара доставляемого отдельно: 1 — 1 

    *   -   Длина коробки, Ширина коробки, Высота коробки

        -   Габаритные размеры коробки, в которую помещаются товары, согласно настройке "Количество штук в коробке".


Редактирование настроек
=======================

Пройдите во вкладку "Параметры доставки" на странице редактирования товара.

.. fancybox:: img/shippings_044.png
    :alt: Методы доставки

Массовое редактирование настроек
================================

Пройдите на страницу товары.

.. fancybox:: img/shippings_045.png
    :alt: Методы доставки

Выделите товары которые необходимо настроить или отредактировать

.. fancybox:: img/shippings_046.png
    :alt: Методы доставки

Нажмите **шестерёнку** и кнопку "Редактировать выбранные" в выпадающем списке

.. fancybox:: img/shippings_047.png
    :alt: Методы доставки

Выберите необходимые поля для редактирования (Вес, Бесплатно, Стоимость доставки, Длина коробки, Ширина коробки, Высота коробки, Максимальное количество штук в коробке, Минимальное количество штук в коробке)

.. fancybox:: img/shippings_048.png
    :alt: Методы доставки

Обновите все выбранные товары на одной странице

.. fancybox:: img/shippings_049.png
    :alt: Методы доставки

Экспорт/импорт
==============

Параметры доставки доступны для обновления с помощью импорта из CSV.

.. list-table::
    :header-rows: 1
    :stub-columns: 1
    :widths: 30 30 30

    *   -   Поле импорта/экспорта
        -   Описание
        -   Значение поля

    *   -   Product code
        -   Обязательное поле, необходимо для идентификации товара.
        -   Код обновляемого товара

    *   -   Language
        -   Язык. Обязательное поле. 
        -   'ru', 'en' и т.д.

    *   -   Weight
        -   Вес
        -   ``0.25``

    *   -   Shipping freight
        -   Стоимость доставки
        -   ``50.00``

    *   -   Free shipping
        -   Бесплатная доставка
        -   ``N`` или ``Y``

    *   -   Box size
        -   Размеры коробки
        -   ``length:20;width:30;height:3``

    *   -   Items in box
        -   Количество штук в коробке
        -   ``min:1;max:1``

.. fancybox:: img/shippings_050.png
    :alt: Методы доставки

.. important::

    Рекомендуем настроить несколько товаров и сделать их экспорт в CSV, для создания эталонной таблицы и правильного обновления остальных товаров.

    Товары идентифицируются по коду товара (артикулу), для безошибочной работы экспорта/импорта у всех товаров должны быть уникальные артикулы.