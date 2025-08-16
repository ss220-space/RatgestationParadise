Шаг 1: Анализируйте путь объекта

Возьмите полный путь объекта из кода:
code\game\gamemodes\cult\cult_items.dm

Шаг 2: Постройте путь спрайта

Уберите корневую часть /obj/item/

Добавьте префикс папки спрайтов:
icons/mob/inhands/clothing (для одежды)
icons/mob/inhands/obj (для других предметов)

Смотрим на путь объекта:
/obj/item/melee/cultblade

Уберите корневую часть /obj/item/

Добавляем суффикс:

icons/mob/inhands/obj + melee/cultblade.dmi + _left/right


