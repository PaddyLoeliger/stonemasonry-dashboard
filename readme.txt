Database of 123 shear and compression tests on stone masonry walls reported in the literature.

Paper reference: Vanin F., Zaganelli D., Penna A., Beyer K. (2017). Estimates for the stiffness, strength and drift capacity 
of stone masonry walls based on 123 quasi-static cyclic tests reported in the literature. Bullettin of Earthquake Engineering

The database is contained in 'Vanin et al. (2017) DatabaseStoneMasonry.xls'.

The folder '01_data' contains the hysteretic curves ('01_experimental_curves') and the derived envelopes ('02_envelopes')
of the tests for which these data are available. Such tests are labelled in the database in the field 'Availability of F-? curve'
(field 65). Data are provided as comma-separated files .csv, where the three-digit number of the file corresponds to the ID of the 
tests reported in the first field of the database (ex.: curve021.csv, envelope021.csv). 
The structure of these files includes the test unit name and the reference of the source in the first two lines, a header 
specifying the content and units of each column in lines 3 and 4, and the data starting from the 5th line. The columns contain the 
top displacement, in mm, as reported in the reference, the top horizontal force in kN and the drift as percent. To calculate the 
drift, where applicable, the difference between the height of the wall and the height of the horizontal LVDT was accounted for. 
Boundary conditions and applied loads are specified in the database.