using Android.App;
using Android.Widget;
using Android.OS;

namespace App3
{
    [Activity(Label = "App3", MainLauncher = true)]
    public class MainActivity : Activity
    {
        protected override void OnCreate(Bundle b)
        {
            base.OnCreate(b);
            TextView scherm;
            scherm = new TextView(this);
            scherm.Text = "Voer hier je naam in!";
            scherm.TextSize = 80;
        
            this.SetContentView(scherm);
           
                   
        }
    }
}
