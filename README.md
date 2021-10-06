# Address Book Console App
My first assignment at university. I created simple address book using java in console environment.

* Το κυρίως Menu του προγράμματος / The main menu of the program. 

![sreen1](https://github.com/StefanosGregory/address_book_console_app/blob/main/Screenshots/screen1.png)

* Εισάγοντας την επιλογή 1 εμφανίζονται οι καταχωρίσεις που υπάρχουν στο αρχείο του προγράμματος / Entering option 1 displays the entries in the program file.

![sreen2](https://github.com/StefanosGregory/address_book_console_app/blob/main/Screenshots/screen2.png)

  * Σε περίπτωση όπου δεν υπάρχουν καταχωρίσεις / In case there are no entries.

![sreen3](https://github.com/StefanosGregory/address_book_console_app/blob/main/Screenshots/screen3.png)

* Εισάγοντας την λέξη no! Ενημερώνει πώς δεν είναι αυτό που περιμένει, δηλαδή το “y” ή το “n” και σου δίνει την ευκαιρία να ξανά προσπαθήσεις / Entering the word no! Informs that it is not what it expect, example "y" or "n" and gives you the opportunity to try again.

![sreen4](https://github.com/StefanosGregory/address_book_console_app/blob/main/Screenshots/screen4.png)

  * Εισάγοντας το “y” / Entering the "y".

![sreen5](https://github.com/StefanosGregory/address_book_console_app/blob/main/Screenshots/screen5.png)

* Επιλέγοντας το 2, ζητάει να εισάγετε όνομα, επίθετο, τηλέφωνο, Email και διεύθυνση / Selecting 2 asks you to enter first name, last name, phone, Email and address.

![sreen6](https://github.com/StefanosGregory/address_book_console_app/blob/main/Screenshots/screen6.png)

  * Σε περίπτωση που δοθούν λάθος στοιχεία / In case of incorrect information.

![sreen7](https://github.com/StefanosGregory/address_book_console_app/blob/main/Screenshots/screen7.png)

* Επιλέγοντας το 3 ζητάει το όνομα του ατόμου για να εμφανίσει την καταχώρηση του. Σε περίπτωση που δεν υπάρχει τέτοια καταχώριση / Selecting 3 asks for the name of the person to display his entry. In case there is no such registration.

![sreen8](https://github.com/StefanosGregory/address_book_console_app/blob/main/Screenshots/screen8.png)

  * Σε περίπτωση που υπάρχει μία τέτοια καταχώρηση / In case there is an entry.

![sreen9](https://github.com/StefanosGregory/address_book_console_app/blob/main/Screenshots/screen9.png)

  * Σε περίπτωση που υπάρχουν περισσότερες από μία τέτοιες καταχωρίσεις / In case there are more than one such entries.

![sreen10](https://github.com/StefanosGregory/address_book_console_app/blob/main/Screenshots/screen10.png)

* Επιλέγοντας το 4 ζητάει το τηλέφωνο του ατόμου για να εμφανίσει την καταχώρηση του.(Ισχύουν οι ίδιες περιπτώσεις και με το πιο πάνω) / Selecting 4 asks for the person's phone to display his entry. (The same applies to the above).

![sreen11](https://github.com/StefanosGregory/address_book_console_app/blob/main/Screenshots/screen11.png)

* Επιλέγοντας το 5 ζητάει το όνομα  της καταχώρησης που θέλετε να επεξεργαστείτε. Ρωτάει αν αυτήν την καταχώρηση θέλετε να επεξεργαστείτε για τον λόγο ότι μπορεί να υπάρχουν πολλές καταχωρήσεις με αυτό το όνομα / Selecting 5 asks for the name of the entry you want to edit. Asks if you want to edit this entry because there may be multiple entries with that name. 

![sreen12](https://github.com/StefanosGregory/address_book_console_app/blob/main/Screenshots/screen12.png)

  * Όταν βρεθεί η καταχώρηση που θέλετε να επεξεργαστείτε / When the entry you want to edit is found.

![sreen13](https://github.com/StefanosGregory/address_book_console_app/blob/main/Screenshots/screen13.png)

  * Επιλέγοντας το 6 ζητάει το όνομα της καταχωρήσης που θέλετε να διαγραφή, σιγουρεύει πια από όλες θέλετε να διαγραφεί σε περίπτωση που υπάρχουν περισσότερες από μία. Ρωτάει για επαλήθευση / Selecting 6 asks for the name of the entry you want to delete, it makes sure which of all entries you want to delete in case there is more than one. Asks for verification.

![sreen14](https://github.com/StefanosGregory/address_book_console_app/blob/main/Screenshots/screen14.png)

 * Επιλέγοντας το 7 τερματίζεται η εφαρμογή / Selecting 7 terminates the application.

![sreen15](https://github.com/StefanosGregory/address_book_console_app/blob/main/Screenshots/screen15.png)

#### Σχόλια / Comments :
 * Όλες οι είσοδοι δεδομένων φιλτράρονται είτε με επαναλήψεις είτε με την μέθοδο εντοπισμού “Error” / All data inputs are filtered either by iterations or by the "Error" detection method.
 * Σε περίπτωση που υπάρξει πρόβλημα με το αρχείο τυπώνει το κατάλληλο μήνυμα / In case there is a problem with the file, it prints the appropriate message.
 * Όταν πρόκειται για διαγραφή ή επεξεργασία μιας καταχώρησης με συνωνυμία υπάρχει δυνατότητα να διαλέξετε / When it comes to deleting or editing a synonymous entry there is a choice to specify.
 * Υπάρχει δυνατότητα επιστροφής στο αρχικό Menu μετά από κάθε ενέργεια που γίνετε / It is possible to return to the Menu after each action you take. 


