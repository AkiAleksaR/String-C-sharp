# String-C-sharp
How to know more about string in C#
🔍 String u C# – Detaljno Objašnjenje i Korišćenje
📌 Šta je string u C#?
string je tip podatka u C# koji predstavlja niz karaktera (tekst). Može se koristiti za čuvanje i manipulaciju tekstualnim podacima.
🛠 Kako deklarisati i inicijalizovati string?
string poruka = "Zdravo, svet!";
Console.WriteLine(poruka);

📌 Objašnjenje:

string poruka → Deklariše promenljivu tipa string.
"Zdravo, svet!" → Inicijalizuje je tekstualnom vrednošću.
Console.WriteLine(poruka); → Štampa sadržaj stringa.

🔹 Čitanje stringa sa konzole (Console.ReadLine())
Console.WriteLine("Unesite vaše ime:");
string ime = Console.ReadLine();
Console.WriteLine("Dobrodošao, " + ime + "!");

📌 Objašnjenje:

Console.ReadLine(); → Korisnik unosi string sa tastature.
🔹 Metode i Svojstva string u C#
1️⃣ Length – Dužina stringa

string tekst = "C# programiranje";
Console.WriteLine(tekst.Length);  // Ispisuje: 17
📌 Length vraća broj karaktera u stringu.

2️⃣ ToUpper() i ToLower() – Mala i velika slova
string tekst = "Hello World";
Console.WriteLine(tekst.ToUpper()); // "HELLO WORLD"
Console.WriteLine(tekst.ToLower()); // "hello world"

📌 Pretvara string u velika/mala slova.

3️⃣ Substring() – Dohvatanje dela stringa
string tekst = "Programiranje";
string deo = tekst.Substring(0, 5);
Console.WriteLine(deo); // "Progr"
📌 Uzimamo prvih 5 karaktera iz stringa.

4️⃣ Replace() – Zamena delova stringa
string tekst = "Ja volim C++";
string noviTekst = tekst.Replace("C++", "C#");
Console.WriteLine(noviTekst); // "Ja volim C#"
📌 Zamenjuje "C++" sa "C#".

5️⃣ Contains() – Provera da li string sadrži određeni tekst
string recenica = "Danas je lep dan!";
bool sadrzi = recenica.Contains("lep");
Console.WriteLine(sadrzi); // true
📌 Proverava da li string sadrži određeni tekst i vraća true ili false.

6️⃣ StartsWith() i EndsWith() – Provera početka/kraja stringa
string tekst = "Dobro jutro!";
Console.WriteLine(tekst.StartsWith("Dobro")); // true
Console.WriteLine(tekst.EndsWith("veče")); // false
📌 Proverava da li string počinje ili završava određenim tekstom.

7️⃣ Trim(), TrimStart(), TrimEnd() – Uklanjanje razmaka
string tekst = "  Pozdrav!  ";
Console.WriteLine(tekst.Trim());      // "Pozdrav!"
Console.WriteLine(tekst.TrimStart()); // "Pozdrav!  "
Console.WriteLine(tekst.TrimEnd());   // "  Pozdrav!"
📌 Uklanja suvišne razmake sa početka i kraja stringa.

8️⃣ Split() – Razdvajanje stringa u niz
string recenica = "C# je sjajan jezik";
string[] reci = recenica.Split(' ');

foreach (string rec in reci)
{
    Console.WriteLine(rec);
}
📌 Razdvaja string na osnovu razmaka i stavlja delove u niz.

9️⃣ Join() – Spajanje niza u string
string[] reci = { "C#", "je", "super" };
string spojeno = string.Join(" ", reci);
Console.WriteLine(spojeno); // "C# je super"
📌 Spaja niz stringova u jedan string sa razmakom.

zadaci za vezbanje
https://github.com/AkiAleksaR/String-c-sharp-exercise

