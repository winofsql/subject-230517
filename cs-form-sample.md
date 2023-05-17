![image](https://github.com/winofsql/subject-230517/assets/1501327/bfada9ee-514b-41c7-96ad-ba25325d338d)

```cs
using System.Diagnostics;

namespace WinFormsApp1
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            Console.WriteLine("こんにちは世界");
            Debug.WriteLine("こんにちは世界");

            MessageBox.Show("こんにちは世界");
        }
    }
}
```
