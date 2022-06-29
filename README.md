# goit-markup-hw-08
.element {
  /* Базовые стили */
}

@media screen and (min-width: ширина-планшета) {
  .element {
    /* Стили планшета */
  }
}

@media screen and (min-width: ширина-десктопа) {
  .element {
    /* Стили десктопа */
  }
}

@media (max-width: 767px) {
  .box {
    margin-bottom: 10px;
  }
}

@media (min-width: 768px) and (max-width: 1023px) {
  .box {
    border: 1px solid black;
  }
}
__________________________________________________________

//стилі для кнопок мобільного меню:
.button-menu{
  dispay: inline-flex;
  border: none;
  margin: 0;
  padding: 0;
  bcg-color: transparent;
}

.button-menu.is-open .icon-menu{
  display: none;
}

.icon-cross{
  display: none;
}

.button-menu.is-open .icon-cross{
  dispaly: block;
}
__________________________________________

.menu-container{
  display: none;
  +styles

  &.is-open{
    display: block;
  }
}

___________________________-
додати медіа-правило для ретини в окремий міксин!!
