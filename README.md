# compare-2-df

Task is to compare two CSV files with differing inputs and rows/columns based on unique identifier, then highlight the changes.

1) download 2 x CSVs from http://www.spezialitaetenliste.ch/
http://www.spezialitaetenliste.ch/File.axd?file=Publications.xlsx
http://www.spezialitaetenliste.ch/File.axd?file=Publications_Next.xlsx

2) transform into dataframes with pandas
3) go the "sheet" Publications
4) go row by row, using GTIN column to compare the two data frames (for loop?)
5) highlight different cells in color?
6) do the same for sheet "Limitationen"



- possibly transform "Einf.-Datum" to date format
