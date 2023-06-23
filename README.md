WIP, not finalized templates and expected to add more as I use them.

# Simple LaTeX Templates

Latex templates I use. Greek language is the primary and the main usefulness of the templates are for people new to LaTeX who want a dual language document and are having issues (with moderncv commands for example). The rest of the description will, for that reason be in Greek

## Ασκήσεις (hw)
Ο φάκελος `hw` περιέχει ένα `.tex` αρχέιο και το παραγόμενο `.pdf` ως παραδείγματα των δυνατοτήτων της συλλογής πακέτων. Το μόνο που χρειάζεται είναι το `.sty` στον φάκελο του project και να συμπεριλφθεί ως package (δηλ. `\usepackage{simplehwgr}`). 
Μπορεί να παραχθούν πολλα warning μετα απο το compile αν έχετε εγκατεστημένα παλαιότερα πακέτα από ότι αναμένεται (στο `.sty` συμπεριλαμβάνεται και η minimum version που έχω χρησιμοποιήσει χωρις αυτό να σημαίνει ότι παλαιότερες δεν λειτουργούν). Μπορούν ως επι το πλείστον να αγνοηθούν αν δεν παρατηρήσετε κάποια απρόβλεπτη συμπεριφορά. Δείτε επίσης στο sample ποιες βασικές εντολές δεν συμπεριλβάνονται.

## Βιογραφικό (cv)
Ενά απλό variation της κλασσικής εμφάνισης του moderncv, με βασική γλώσσα την ελληνική και τα workarounds που επέλεξα για να δουλεύουν link, email κλπ. Υπάρχουν πιο σωστοί τρόποι, με αλλαγές στο .cls του moderncv αλλα ο τρόπος που έχω ανεβάσει είναι λειτουργικός. Ουσιαστικά ένα απλό παράδειγμα. Οι διορθώσεις αφορών την παλία έκδοση του moderncv, δεν ξέρω αν [στο νεο branch](https://github.com/moderncv/moderncv/tree/master) τα προβλήματα έχουν διορθωθεί.
