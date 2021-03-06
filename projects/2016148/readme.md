ΙΟΝΙΟ ΠΑΝΕΠΙΣΤΗΜΙΟ

ΤΜΗΜΑ ΠΛΗΡΟΦΟΡΙΚΗΣ

ΜΑΘΗΜΑ
Κινητά και Κοινωνικά Μέσα
Επιβλέπων καθηγητής: Χωριανόπουλος Κωνσταντίνος

ΕΠΙΛΟΓΗ ΕΡΓΑΣΙΑΣ
Συνεργατική χαρτογράφηση

Λάζαρος Ιορδάνου
ΑΜ: Π2016148

Corfu-Map Editor: https://lazlo54.github.io/corfu-map/

Repository: https://github.com/lazlo54/corfu-map

Σύνοψη:
  Το θέμα της εργασίας είναι η συνεργατική χαρτογράφηση δρόμων για πεζούς στην πόλη της Κέρκυρας. Από την εργασία αναμένεται να μάθουμε να χρησιμοποιούμε πολύ καλά την γλώσσα προγραμματισμού javascript, το API της Google για χάρτες και την βάση δεδομένων Firebase. Με μια πρώτη ματία, η εργασία αναμένεται να είναι πολύ απαιτητική.

Εισαγωγή:
  Πιο συγκεκριμένα, μας δόθηκε ένα προσχέδιο κώδικα πάνω στο όποιο έπρεπε να αναπτύξουμε τα δυο πρώτα παραδοτέα. Ο σκοπός της εργασίας είναι να δημιουργήσουμε διαδρομές στην πόλη της Κέρκυρας και να τις βαθμολογήσουμε ανάλογα με την καταλληλότητα τους για πεζούς. Έπειτα, να μετατρέψουμε την web εφαρμογή σε android εφαρμογή προσθέτοντας επιπλέον λειτουργικότητα. Στην συνέχεια παραθέτονται αναλυτικά ολοι οι συλογισμοί και το σκεπτικό που ειχα κατα την υλοποίηση.

Site που χρησημοποίησα:
  API Guides (https://developers.google.com/maps/documentation/javascript/tutorial)
  API Reference (https://developers.google.com/maps/documentation/javascript/reference/3/)
  API Samples (https://developers.google.com/maps/documentation/javascript/examples/)
  Stack Overflow (https://stackoverflow.com/questions/tagged/google-maps) 


ΜΕΘΟΔΟΙ ΑΝΑΠΤΗΞΗΣ

1ο Παραδοτέο

inteface:
![](https://github.com/lazlo54/cscw/blob/master/projects/2016148/interface.png)

Το πρωτο παραδοτεο ηταν κυριως με την διεπαφη της εφαρμογης. Αρχικα προσθεσα ενα παραθυρο το οποιο να εμφανιζει το geojson αρχειο σε μορφη text,επιτα δημιουργισα ενα κουμπι το οποιο εμφανιζει και εξαφανιζει αυτο το παραθυρο. Στη συνεχεια εβαλα καποια λειτουργικα κουμπια σχετικα με την μορφοποιηση των features που δημιουργει ή επεξεργαζεται ο χρηστης, αυτα τα κουμπια ειναι ενα πληκτρο που διαγραφει ολα features πανω στον χαρτη και αλλο ενα που διαγραφει τα επελεγμενα features(με τη χρηση προγραμματισμου εβαλα ο χρηστης να μπορει να επιλεξει πολλαπλα features ταυτοχρονα και του δεινω την δυνατοτητα να μπορει να αλλαξει βαθμολογια ή να διαγραψει πολλα features ταυτοχρονα αυτο συμβαινει επειδη η προσορινη feature εντασετε μεσα σε ενα πινακα, επισης οταν γινει η επιλογη μιας features τοτε αν ο χρηστης θελει να ξε-επιλεξει την features μπορει απλα να ξανα πατησει πανω της και τοτε δεν ανηκει πια στις στον πινακα των επιλεγμενων feature).Δημιουργησα τα καταλληλα κουμπια που θετουν στα επελεγμενα features την επιθυμητη βαθμολογια εχοντας ενα κουμπι με το αναλογο χρωμα για καθε βαθμολογια.Επισης μες το μενου υπαρχει το κουμπι που επιτρεπει στον χρηστη να κατεβασει το geojson αρχειο και αλλο ενα κουμπι που δινει την δινατοτητα στον χρηστη να επιλεξει ολο το text αρχειο που εμφανιζεται στο παραθυρο για να μπορει να το αντιγραχει αυτουσιο.Η εφαρμογη πληρει ολα τα ζητουμενα του παραζοτεου και επισης παρεχει περισοτερες λειτουργειες απο το ζητουμενο, οι οποιες εγιναν για την πιο ευκολη χρηση της εφαρμοφης.


2o Παραδοτέο 

Το δεύτερο παραδοτέο δεν μπόρεσα να το κάνω.
