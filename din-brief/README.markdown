#German DIN Letter
A template for a German DIN letter with _four colour sets_ (blue, orange, green, grey),
_various font types_ and _easy modifications of the header and footer_.
The four colour sets are the same provided by the _moderncv_ class.
Thus this DIN letter template can be perfectly used in combination with a Curriculum Vitae using
the template provided in this repository: `../cv`.

##Files
###`Brief.tex`
The main document, where the content of the letter is written.
See the (German) comments in there for a more detailed explaination.

###`incl/`
####`dateup.lco`
Places the date at a specific position on the first page.
Inclusion of this file in `Brief.tex` will enable it.

####`Fonts.tex`
Select the font you like simly by uncommenting the corresponding lines in here.
(Don't forget to comment out other font types)

####`fromaddress.lco`
**Important**  
Define your own name, adress, phone number and (optional) bank account detailes in here.

####`headerfooter.lco`
If you like to modify the header and / or footer of the letter, do it here.

####`textwidth.lco`
Configuration of the page layout.

##Source
Original version was retreived from [Matthias Pospiech](http://www.matthiaspospiech.de/latex/vorlagen/)
([`Brief.zip`](http://www.matthiaspospiech.de/download/latex/vorlagen/brief/Brief.zip)).
This here is a modified version by myself.