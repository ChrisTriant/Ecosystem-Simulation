# -Ecosystem-Simulation

Για την εκπόνηση της εργασίας ακολουθήσαμε την ακόλουθη λογική και μεθοδολογία:
Δώσαμε προκαθορισμένο αριθμό λόφων (2) τυχαίου μεγέθους. Η τοποθέτηση τους γίνεται με τυχαίο τρόπο κι αν τυχών πέσουν tiles λόφου πάνω σε νερού τότε το νερό δεν επικαλύπτεται.
Τα lakesize και hillsize είναι τυχαία και ανάλογα του terrain size.
Υποθέσαμε ότι τα σαρκοφάγα χορταίνουν με ενα γεύμα και δεν χρειάζεται να φάνε συγκεκριμένο αριθμό τροφής.
Ο σολωμός είναι πάντα ενήλικος αλλά μόλις γεννηθεί θεωρείται νεογέννητος για να μην αναπαράγονται επ άπειρον.
Παρόμοια αντιμετωπίσαμε και τα φυτά.
Οι πιθανότητες αρρώστιας και αναπαραγωγής στα φυτά έχουν υλοποιηθεί ως πίνακες διαφορετικών και τυχαίων πιθανοτήτων ανάλογα με το είδος των φυτών(seeded/seedless).
Τα ζώα που βρίσκονται σε χειμερία νάρκη μπορούν να αναπτυχθούν αλλά και να φαγωθούν (αν αυτό είναι δυνατό).Επίσης οι μετρητές πείνας τους δεν μεταβάλονται.
Τα σαρκοφάγα μπορούν να φάνε άλλα ζώα του είδους τους(κανιβαλισμός) αν πεινάνε πολύ.
Η ανήλικη αρκούδα τρέφεται όπως τα υπόλοιπα σακοφάγα ενώ η ενήλικη αυτομάτως τρώει οποιοδήποτε ζώο.
Τα ζώα μετακινούνται εώς speed tiles(προς τυχαία κατεύθυνση) αν δεν βρούν εμπόδιο.
Έχει παρατηρηθεί πρόβλημα στην τυχαιότητα με την οποία η rand() βγάζει αριθμούς με αποτέλεσμα να είναι πολύ συχνή η εμφάνιση ενός μόνο είδους φυτού στις εκάστοτε περιοχές.
Το πρόγραμμα υλοποιήθηκε σε visual studio και για την χρήση χρωμάτων μεταφέρθηκε στα linux της σχολής.
(Στο .zip περιέχεται και Makefile)

Εντολή για compile: make
Εντολή για εκτέλεση: ./Eco

Developers:
Θοδωρής Παγκρακιώτης: sdi1700272
Χρήστος Τριανταφύλλου-Αρχολέκας: sdi1700166
