text_files = \
	define.utf \
	start.utf \
	Multi_prog.utf

out = \
	pscript.dat

all= $(out)

$(out): $(files)
	@echo "Création du script..."
	@nscmake -o $(out) $(text_files)
	@echo "Script compilé."

clean:
	@if test -f arc.nsa; then rm -f arc*.nsa && echo "Les arc.nsa supprimé avec succès"; else echo "Aucun arc.nsa présent." ; fi
	@if test -f $(out); then rm -f $(out) && echo "$(out) supprimé avec succès."; else echo "Aucun $(out) présent." ; fi



.PHONY: all clean