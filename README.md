# Physiotheraphy-notes-to-lear-C-syntax
My PT notes to learn syntax in C++
#include <string>
using namespace std;

struct OsservazioniAttenzione {
    bool attenzioneDrasticamenteRidotta = true;
    string durataAttenzione = "secondaria, breve, di pochi secondi";
    bool stimoliVisiviEfficaci = false;
    bool stimoliSonoriEfficaci = false;
};

struct ComportamentoGuida {
    bool evitaOstacoli = false;
    bool tentaSpingerePacholki = true;
    string comprensioneCompito = "limitata";
};

struct AbilitaGuida {
    string guidaLineaRetta = "relativamente buona (avanti e indietro)";
    string sterzataDestra = "molto difficoltosa";
    string sterzataSinistra = "molto difficoltosa";
};

struct FattoriLimitanti {
    bool manicheTroppoLunghe = true;
    string effettoSuPresa = "riduzione del controllo e della presa delle mani";
};

struct SedutaTerapia {
    int durataMinuti = 45;
    OsservazioniAttenzione attenzione;
    ComportamentoGuida comportamento;
    AbilitaGuida abilita;
    FattoriLimitanti fattori;
};

int main() {
    SedutaTerapia sedutaOggi;

    // Notatka logiczna z przebiegu terapii
    return 0;
}
