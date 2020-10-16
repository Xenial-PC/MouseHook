# MouseHook
This is a public release of my mouse hook ive been using for 2 years now 

### How To Use
~~~ private MouseHook.MouseHook _mh;
private void YourForm_Load(object sender, EventArgs e)
        {
            _mh = new MouseHook.MouseHook();
            _mh.SetHook();

            _mh.MouseMoveEvent += mh_MouseMoveEvent;
            _mh.MouseClickEvent += mh_MouseClickEvent;
            _mh.MouseDownEvent += mh_MouseDownEvent;
            _mh.MouseUpEvent += mh_MouseUpEvent;
        }

 private static void mh_MouseDownEvent(object sender, MouseEventArgs e)
        {
            switch (e.Button)
            {
                case MouseButtons.Left:
                    
                    break;
                case MouseButtons.Right:
                    
                    break;
            }
        }

        private static void mh_MouseUpEvent(object sender, MouseEventArgs e)
        {
            switch (e.Button)
            {
                case MouseButtons.Left:
                    
                    break;
                case MouseButtons.Right:
                    
                    break;
            }
        }

        private static void mh_MouseClickEvent(object sender, MouseEventArgs e)
        {
        }

        private static void mh_MouseMoveEvent(object sender, MouseEventArgs e)
        {
        }
