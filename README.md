## Τελική Αναφορά
## **ΕΠΙΚΟΙΝΩΝΙΑ ΑΝΘΡΩΠΟΥ ΥΠΟΛΟΓΙΣΤΗ**
## **ΓΙΑΝΝΙΟΣ ΑΝΤΩΝΙΟΣ Π2013153**
#### [Αποθετήριο HCI](https://github.com/p13gian1/hci)

#### [Αποθετήριο κώδικα 1ου μέρους]( https://github.com/p13gian1/D3js-US-educational-attainment)

#### [Σύνδεσμος εκτελέσιμου  1ου μέρους ]( https://p13gian1.github.io/D3js-US-educational-attainment/)

#### [Αποθετήριο κώδικα 2ου μέρους](https://github.com/p13gian1/D3js-US-educational-attainment-part2)

#### [Σύνδεσμος εκτελέσιμου  2ου μέρους](https://p13gian1.github.io/D3js-US-educational-attainment-part2/)

#### [Αποθετήριο κώδικα 3ου μέρους](https://github.com/p13gian1/D3js-US-educational-attainment-part3)

#### [Σύνδεσμος εκτελέσιμου  3ου μέρους ]( https://p13gian1.github.io/D3js-US-educational-attainment-part3/)

### Σύνοψη
#### To θέμα της εργασίας ήταν η Οπτικοποίηση Δεδομένων. Η εργασία βασίστηκε πάνω στον κώδικα του αρχικού αποθετηρίου του μαθήματος [D3js-US-educational-attainment](https://github.com/ioniodi/D3js-US-educational-attainment). Για την οπτικοποίηση των δεδομένων χρησιμοποιήθηκε κυρίως η βιβλιοθήκη της Javascript d3.js. Η ανάπτυξη της εργασίας έγινε με την χρήση HTML, Javascript και CSS. Στο 1ο μέρος της εργασίας περιλαμβάνονται 3 αρχικά διαγράμματα τα . Στο 2ο μέρος αντικαστάθηκαν από 3 νέα διαγράμματα τα οποία οπτικοποιούν τα ίδια δεδομένα με τα αρχικά. Και στο 3ο μέρος δημιουργήθηκαν 3 νέα διαγράμματα πάνω σε εντελώς νέα δεδομένα.  Λόγω πίεσης του χρόνου δεν ήταν εφικτό να τελειοποιηθούν πλήρως τα νέα διαγράμματα όπως θα ήθελα.

### Σύντομη Εισαγωγή
#### Η Οπτικοποίηση Δεδομένων, για να είναι επιτυχημένη, θα πρέπει να γίνει σωστή επιλογή του κατάλληλου διαγράμματος προκειμένου να οπτικοποιήσουμε ένα συγκεκριμένο σετ δεδομένων. Το διάγραμμα αυτό μπορεί να είναι απλό, μπορεί επίσης να είναι και διαδραστικό. Τα διαδραστικά διαγράμματα καλύτερη οπτικοποίηση των δεδομένων με αμεσότερο τρόπο.
Στην συγκεκριμένη εργασία η διαδραστικότητα των διαγραμμάτων καθώς και της όλης της σελίδας έγινε με την χρήση της γλώσσας Javascript και CSS HTML. Επίσης η επιλογή των νέων διαγραμμάτων του 2ου και 3ου μέρους έγινε με αναζήτηση στο διαδίκτυο σε σελίδες που ενσωματώνουν παραδείγματα της D3.js βιβλιοθήκης.
Επίσης χρησιμοποιήθηκαν διαφορετικά σετ δεδομένων σε διαφορετική μορφή (json, csv, tsv). Το parsing ώστε να γίνει η επεξεργασία των δεδομένων, έγινε με την χρήση της βιβλιοθήκης d3.js.  Τα δεδομένα που επιλέχθηκαν για οπτικοποίηση είναι από τον Οργανισμό Ηνωμένων Εθνών που αφορούν στην αναλογία ανδρών και γυναικών σε ορισμένες χώρες του πλανήτη κατά το έτος 2004.
 Στο 2ο μέρος η αντικατάσταση των διαγραμμάτων από 3 νέα έγινε επίσης, με την αναζήτηση σε παραδείγματα  της βιβλιοθήκης d3.js τα οποία τροποποιήθηκαν καταλλήλως ώστε να ενσωματώνουν τα δεδομένα του 1ου μέρους. Πολλές φορές η δυνατότητα αυτή δεν ήταν εφικτή καθώς τα δεδομένα του παραδείγματος ήταν είτε διαφορετικά είτε είχαν επιπλέον στοιχεία ή κατηγορίες.
Τέλος έγινε προσπάθεια να χρησιμοποιηθεί για λόγους συμβατότητας μόνο η έκδοση 4 της βιβλιοθήκης d3.js.

### Σύντομη ανάπτυξη σχετικών έργων και εργαλείων
#### Όπως ειπώθηκε, χρησιμοποιήθηκαν HTML, Javascript και CSS. Τα διαγράμματα της βιβλιοθήκης d3.js είναι svg (scalable Vector Graphics) διαγράμματα. Στα διαγράμματα αυτά μπορούν να ενσωματωθούν δεδομένα τα οποία μπορούν να απεικονιστούν φτιάχνοντας γεωμετρικά σχήματα τα. Τα σχήματα αυτά έχουν χαρακτηριστικά τα οποία διαμορφώνονται από αυτά τα δεδομένα. Π.χ η δημιουργία παραλλήλογραμμου φτιάχνει ένα ραβδόγραμμα. Τα δεδομένα ενσωματώνονται με την χρήση κατάλληλων εντολών της d3.js  τα οποία κάνουν parsing τα δεδομένα αυτά. Π.χ  η d3.json(namefile.json, data), d3.csv(namefile.csv, data), d3.tsv(namefile.tsv,data) κάνουν αντίστοιχα parsing στα αρχεία namefile με τύπο json, csv ή tsv και δημιουργούν ένα array με όνομα data. Έπειτα το array αυτό ενσωματώνεται και αντιστοιχείται στα γεωμετρικά στοιχεία του svg (π.x rect, arcs, dots κλπ) ώστε να δημιουργηθεί το διάγραμμά μας. Ακόμη η βιβλιοθήκη d3.js μας δίνει την δυνατότητα να κάνουμε scaling στα δεδομένα μας και έτσι να προσαρμοστούν στους άξονες που ορίζουμε. Η διαδραστικότητα των διαγραμμάτων επιτυγχάνεται α) με την χρήση της βιβλιοθήκης responsivevoice.js (η οποία μετατρέπει το κείμενο σε ομιλία στο 1ο και 2ο μέρος), β)με την χρήση CSS styling των στοιχείων της HTML πάνω σε γεγονότα καθορισμένα από τον χρήστη (mouseover, mouseclick) γ) την χρήση tooltips τα οποία απεικονίζουν τα δεδομένα σε αντίστοιχες θέσεις των διαγραμμάτων. Και τέλος δ) η d3.js δίνει πολλά επιπλέον εργαλεία όπως η δυνατότητα animation όλων των στοιχείων του διαγράμματος.

### Μέθοδος και τεχνικές ανάπτυξης
#### H συγγραφή του κώδικα έγινε σε περιβάλλον Sublime Τext editor, και εκτέλεση των σελίδων σε WAMPSERVER. Δεν χρησιμοποιήθηκε το github pages λόγω αργής ταχύτητας και απόκρισης των αλλαγών στον κώδικα. Το οποίο και θα με δυσκόλευε στην τροποποίηση των υπαρχόντων διαγραμμάτων και στην δημιουργία νέων.  Έτσι προτίμησα να φτιάξω τον κώδικα στο παραπάνω περιβάλλον και έπειτα να το ανεβάσω στο github. Για τον έλεγχο – testing του κώδικα χρησιμοποίησα τους browsers Chrome, Firefox και Microsoft Edge. Τέλος για την επεξεργασία των δεδομένων και την εξαγωγή τους σε CSV χρησιμοποίησα το Microsoft Excel.
Τα δεδομένα του 1ου γραφήματος του 3ου μέρους εξάχθηκαν από τον OHE στην παρακάτω σελίδα
[UNdata](http://data.un.org/Data.aspx?d=GenderStat&f=inID%3a2)
Η εργασία στηρίχθηκε στις παρακάτω εργασίες οι οποίες αποτέλεσαν την κύρια ιδέα για να τροποποιηθούν τα υπάρχοντα διαγράμματα ή να δημιουργηθούν νέα.
Στο 2ο μέρος  το πρώτο διάγραμμα στηρίχθηκε στην παρακάτω εργασία
[Radial Bar Chart built with D3](https://bl.ocks.org/AntonOrlov/6b42d8676943cc933f48a43a7c7e5b6c)
Στο 2ο μέρος το δεύτερο διάγραμμα στηρίχθηκε στην παρακάτω σελίδα
[Tree diagrams](http://www.d3noob.org/2014/01/tree-diagrams-in-d3js_11.html)
Στο 2ο μέρος  το τρίτο διάγραμμα στηρίχθηκε στην παρακάτω εργασία
[US State Map] (http://bl.ocks.org/NPashaP/a74faf20b492ad377312)
Στο 3ο μέρος το 1ο διάγραμμα στηρίχθηκε στην παρακάτω εργασία: [World Tour]( https://bl.ocks.org/mbostock/4183330)
Επίσης στο 3ο μέρος το 2ο διάγραμμα στηρίχθηκε στην παρακάτω εργασία
[Spiral Heatmap](https://bl.ocks.org/tomshanley/0a024581fd0b7c4e483203d5bff9631b)
Τέλος λόγω χρόνου δεν κατάφερα να υλοποιήσω στο δεύτερο και τρίτο διάγραμμα του 3ου μέρους την δυνατότητα να κάνει parsing αρχεία με νέα δεδομένα αλλά έμειναν με υποτυπώδη αρχεία παραδείγματος.  


### Screenshots
![Diagram 1](https://github.com/p13gian1/Final-Report-HCI/blob/master/1.JPG)
![Diagram 2](https://github.com/p13gian1/Final-Report-HCI/blob/master/2.JPG)

### Συμπεράσματα
#### Η Οπτικοποίηση Δεδομένων αποτελεί μια ενδιαφέρουσα πτυχή στον προγραμματισμό η οποία μου έδωσε την δυνατότητα να εμβαθύνω περισσότερο στην ΗTML, Javascript, CSS. Δεν μου φάνηκε ιδιαίτερα δύσκολη ως μεθοδολογία, απλώς απαιτείται περισσότερος χρόνο για να εμβαθύνει κάποιος πλήρως και αποτελεσματικά στην συγκεκριμένη βιβλιοθήκη και μεθοδολογία. Επίσης με την αναζήτηση στο διαδίκτυο διαπίστωσα πως υπάρχουν χιλιάδες παραδείγματα τα οποία δίνουν μια πολύ καλή βάση σε κάποιον για να ξεκινήσει και να φθάσει σε ένα ικανοποιητικό επίπεδο. Φυσικά λόγω  πίεσης χρόνου αυτό δεν κατέστη δυνατό για εμένα, όμως παρόλα αυτά αποτέλεσε μια πολύ καλή αρχή. 



