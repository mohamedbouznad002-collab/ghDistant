HOOK PRE-COMMIT — INSTALLATION
 
Ce hook verifie et enregistre chaque commit dans suivi/commitInfo.txt.
 
Pour l'installer apres avoir clone le depot :
  cp githooks/pre-commit .git/hooks/pre-commit
  chmod +x .git/hooks/pre-commit
 
Repondre 'y' pour activer la trace, 'n' ou Entree pour ignorer.
