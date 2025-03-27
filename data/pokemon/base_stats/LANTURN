	db DEX_LANTURN ; pokedex id

	db  125,  58,  58, 67,  76
	;   hp  atk  def  spd  spc

	db WATER, ELECTRIC ; type
	db 75 ; catch rate
	db 150 ; base exp

	INCBIN "gfx/pokemon/front/lanturn.pic", 0, 1 ; sprite dimensions
	dw ElectrodePicFront, ElectrodePicBack

	db ELECTRO_BALL, SUPERSONIC, WATER_GUN, THUNDER_WAVE ; level 1 learnset
	db GROWTH_SLOW ; growth rate

	; tm/hm learnset
	tmhm SURF,        AMNESIA,    ICE_BEAM,   HYPER_BEAM,         THUNDERBOLT,  \
	     BLIZZARD,      HIDDEN_POWER
	; end

	db 0 ; padding
