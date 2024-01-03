 public static void ResetControlls()
        {
            ButtonDictionary.Clear();
            ButtonDictionary.Add(CButtons.Left, new ButtonMapper(new[] { Keys.Left }, new[] { Buttons.DPadLeft }));
            ButtonDictionary.Add(CButtons.Right, new ButtonMapper(new[] { Keys.Right }, new[] { Buttons.DPadRight }));
            ButtonDictionary.Add(CButtons.Up, new ButtonMapper(new[] { Keys.Up }, new[] { Buttons.DPadUp }));
            ButtonDictionary.Add(CButtons.Down, new ButtonMapper(new[] { Keys.Down }, new[] { Buttons.DPadDown }));
            ButtonDictionary.Add(CButtons.A, new ButtonMapper(new[] { Keys.S }, new[] { Buttons.A }));
            ButtonDictionary.Add(CButtons.B, new ButtonMapper(new[] { Keys.D }, new[] { Buttons.B }));
            ButtonDictionary.Add(CButtons.X, new ButtonMapper(new[] { Keys.A }, new[] { Buttons.X }));
            ButtonDictionary.Add(CButtons.Y, new ButtonMapper(new[] { Keys.W }, new[] { Buttons.Y }));
            ButtonDictionary.Add(CButtons.Select, new ButtonMapper(new[] { Keys.Space }, new[] { Buttons.Back }));
            ButtonDictionary.Add(CButtons.Start, new ButtonMapper(new[] { Keys.Enter }, new[] { Buttons.Start }));
            //buttonDictionary.Add(CButtons.L, new ButtonMapper(new[] { Keys.NumPad4 }, new[] { Buttons.LeftShoulder }));
            //buttonDictionary.Add(CButtons.R, new ButtonMapper(new[] { Keys.NumPad6 }, new[] { Buttons.RightShoulder }));
        }