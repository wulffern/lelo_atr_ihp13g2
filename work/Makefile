
#- Core makefile provides the following commands:
# -----------------------------------------------------------
# ip: generate ../design/<LIB> from ../cic/ip.json
# gds: generate gds/<CELL>.gds
# cdl: generate cdl/<CELL>.cdl
# xlvs: Check cdl/<CELL>.cdl versus ../design/<LIB>/<CELL>.mag
# lpe: Extract parasitics lpe/<CELL>.spi
# drc: Run design rule checks on ../design/<LIB>/<CELL>.mag
# -----------------------------------------------------------

PREFIX=
LIB=LELO_ATR_IHP13G2
CELL=LELO_ATR

#- Provide cells you want to check for the lvsall drcall commands
CELLS= PCH_2CTOP PCH_4CTOP PCH_8CTOP PCH_12CTOP NCH_2CTOP NCH_4CTOP NCH_8CTOP NCH_12CTOP

include ../tech/make/core.make
