# scriptcorrectioncheck
#./bin/bash
echo "Merci d'avoir entré les informations suivantes:"
echo "Nom du PC: $1"
echo "Adresse MAC : $2"
echo "Adresse IP : $3"

echo "$1$2$3" >> ConfigurationReseau.txt
