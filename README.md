# SoundBox-Files First Tutorial
Here are the files from the first tutorial which was the SoundBoard one @ https://www.youtube.com/watch?v=_-doHB87IyY


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

