SASS

```scss
.wrapper {
  display: inline-block;
  position: relative;
}

.password {
  padding-right: 30px;
}

.passwordIcon {
  display: inline-block;
  position: absolute;
  top: 50%;
  right: 10px;
  width: 19px;
  height: 11px;
  margin-top: -5px;
  background: url("./img/eye.svg");
  cursor: pointer;
  z-index: 2;

  &:hover {
    background: url("./img/eye_hover.svg");
  }

  &.active {
    background: url("./img/eye_0.svg");

    &:hover {
      background: url("./img/eye_0_hover.svg");
    }
  }
}

```
