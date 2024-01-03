Line 66-73

``_backgroundWidth = (int)Math.Ceiling(Game1.WindowWidth / (double)(32 * _scale) + 1) * 32 * _scale;

  _menuRectangle = new Rectangle(
    Game1.WindowWidth / 2 - _menuWidth * _scale / 2,
    Game1.WindowHeight / 2 - _menuHeight * _scale / 2, _menuWidth * _scale, _menuHeight * _scale);``

handles the main menu file select screen.
_backroundWidth is the rectangle for `Content/Menu/menuBackground.png`
_menuRectangle is the black rectangle


Line 106 
``// draw the black background
  spriteBatch.Draw(Resources.SprWhite, _menuRectangle, Color.Black);""