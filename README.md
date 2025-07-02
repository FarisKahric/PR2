# PR2
Ispitni zadaci PR2

Redoslijed :
- 2.9.2024 G1
- 15.7.2024 
- 27.6.2024
- 18.9.2023
- 19.7.2022
- 30.6.2022
- 16.7.2021 G1
- 16.7.2021 G2
- 25.6.2021 G1

?=.    provjera kolicine svega
?=.*  provjera necega u stringu
- pripaziti na friend int operator -
- kod nasljedjivanja ide : public Osoba
- virtual ide ispred destruktora u nasljedjivanju (na prvi destruktor)
- kod nasljedjivanja takodjer prva klasa mora imati virtual void Info() {} a u drugoj isto samo cout<<*this;
- kod nasljedjivanja takodjer konstruktor kopije mora imati : Osoba (obj)
- ako vektor nije pokazivac ide _ocjena = obj._ocjena a ako jest new vector Osoba(*_obj.)
- nekad u operatoru<< zajebava const ispred reference pa se to brise ako ne mozes pristupiti elementima
- pripaziti kod validiranja teksta i lozinki na ? lozinka : NIJEVALINDA;
- ono sto se salje kao parametar u posljednjoj ADD funkciji su parametri PosaljiMail threada
- u prosjecima nek i suma bude float zbog konacnog rezultata
- kada operator== podvlaci i pise previse parametara ides na 1 parametar obj sa this poredis
- static int > poslije klase        int Igrac::_id = 1;
- pripaziti na *obj._trenutno 
- mozda nekad zajebava <= u konstruktoru ako enumeracija nema toliko elemenata
- u operatorima i kad se provjerava uslov, ako se nesto dva puta ispisuje probaj break;
- ako thread PosaljiMail prekida ispis drugim ispisima, koristiti Get metode za ispis, ne direktno
- u operatoru [] dereferenciranje ide samo kod niza pokazivaca
- strstr pretraga sadrzaja u stringu ( string, sadrzaj )!=nullptr
- operator== - stringovi se provjeravaju direktno a charovi sa strcmp
- ako neka klasa ima pokazivac na kolekciju, konst kopije ide new Kolekcija <> (*obj._kolekcija) a inace obicna ide samo = obj._kolekcija
- kod vektora isto obicna ide samo = obj._vektor ali kod pokazivaca moras sa FOR proci kroz sve clanove i u svaki pushback(new Vektor(*obj._vektor[i]);
- kad god imas u enumeraciji =1, ne ide funkcija ispisa te moras [razred - 1]
- pripaziti da ne brises 2 puta istu memoriju

