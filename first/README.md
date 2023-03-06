```
Description: First Sim Added to this repo.
	Demonstrates a, "bullet with energy radiating backward toward the shooter".

	mar34.txt			a little pre built sim with the two organism already setup

	seed_bullet2.kf		the seed file to use for the bullet strain
	seed_ShootNew.kf	the seed file to use for the shooter strain
	seed_shoot55.kf		different shooter variant (not great)
	seed_shoot56.kf		different shooter variant (not great)

	dna_bullet2.kf		a save from an evolved bullet
	dna_ShootNew.kf		a save from an evolved shootet

; Setup the strains as follows:
;
; Strain 0: ShootNew
; Protected Code Blocks: 11
; Protected Instructions: MAKE-BARRIER BROADCAST SAY SPAWN 
; Instruction Modes: EAM=640 MSE=100 GE=100 GS=20 SPM=45 
;    BM=2 SAM=32 
; MaxApply=10 MaxCB=100 StrandLen=4 
;
;
; Strain slot #5 in your simulation should be confiugred for
; the bullet. Which uses these parameters:
;
; Strain 5: bullet2
; Protected Code Blocks: 0
; Protected Instructions: MAKE-BARRIER SPAWN 
; Instruction Modes: LM=1 EAM=520 ROM=1 SEM=1024 
; MaxApply=10 MaxCB=100 StrandLen=4 
;
; The initial seed program can be "nullseed.kf"

```
