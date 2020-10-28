# tastaturatelefonculitere
tastatura telefon cu litere proiect incomplet

sunteti invitati sa modificati proiectul si sa folositi hashtable pentru a cauta interactiv intro lista de cuvinte daca se pot forma cuvinte apasand un sir de taste si sa oferiti utilizatorului posibiliteata sa aleaga cuviantul care se poate forma sau sa validati daca exista in lista un anumit cuvant care sa corespunda literelor apasate pe tastele numeriele ale telefonului. nu respecta chiar tastatura telefonului dupa cum vedeti


proiectul ar fi aici https://www.youtube.com/watch?v=PIeiiceWe_w


Ce este :

namespace tastaturatelefon
{
    public partial class ctrlbuton : UserControl
    {
        public ctrlbuton()
        {
            InitializeComponent();
        }
        
public Form1 frm;

private void ctrlbuton_Load(object sender, EventArgs e)
        {
            try
            {
                frm = (Form1)this.ParentForm;
            }
            catch { }
        }
        }
}

? .

Explicatie : Se informeaza compilatorul de c# inclus in  ms visual studio de faptul ca pe Form1 exista o variabila sau metoda. Form1 fiind de tip Static Thread cred ca nu este o eroare. Acest lucru permite apelarea de metode sau accesul la date publice din Form1 fara a utiliza pointeri sau delegate...
