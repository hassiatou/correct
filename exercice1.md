mkdir cli_tmp
touch cli_tmp/je_suis_dans_tmp.text
cd cli_tmp
touch in_cli_tmp.txt
cd cli_tmp
rm -rf je_suis_dans_tmp.text
rm -rf cli_tmp
mkdir grand_parent parent grand_frere grande_soeur ami connaissances
cd grand_frere
touch bachir
mv bachir
touch bachir.text
mv bachir.text/ami
cp -r ami parent
rm -rf bachir
pwd
cd ~
rm -rf cli_tmp
