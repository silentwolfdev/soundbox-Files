# SoundBox-Files First Tutorial


```C#
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Media;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace soundbox
{
    public partial class mainForm : Form
    {
        public mainForm()
        {
            InitializeComponent();
        }

        private void clapButton_Click(object sender, EventArgs e)
        {
            SoundPlayer sp = new SoundPlayer(soundbox.Properties.Resources.Clap);
            sp.Play();

        }

        private void drumButton_Click(object sender, EventArgs e)
        {
            SoundPlayer sp = new SoundPlayer(soundbox.Properties.Resources.Drum);
            sp.Play();
        }

        private void highthatButton_Click(object sender, EventArgs e)
        {
            SoundPlayer sp = new SoundPlayer(soundbox.Properties.Resources.High_Hat);
            sp.Play();
        }
    }
}

```

