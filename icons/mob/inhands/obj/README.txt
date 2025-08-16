Шаг 1: Анализируйте путь объекта

Смотрим на путь объекта:
/obj/item/melee/cultblade

Уберите корневую часть /obj/item/

Шаг 2: Постройте путь спрайта

Добавьте префикс папки спрайтов:
icons/mob/inhands/clothing (для одежды)
icons/mob/inhands/obj (для других предметов)

Добавляем суффикс:

icons/mob/inhands/obj + melee/cultblade.dmi + _left/right



