/* courtesy Ian Darwin and Geoff Collyer, Softquad Inc. */
digraph unix {
	fontname="Helvetica,Arial,sans-serif"
	node [fontname="Helvetica,Arial,sans-serif"]
	edge [fontname="Helvetica,Arial,sans-serif"]
	node [color=lightblue2, style=filled];
	"I.12" -> "Proposition 31";
	
	# This is for the I.12 
	"I.Post.3" -> "I.12";
	
	"I.10" -> "I.12";
	# This is for the I.10 
	"I.1" -> "I.10";
	"I.9" -> "I.10";
	"I.Def.20" -> "I.10";
	"I.4" -> "I.10";

	
	
	
	"I.Post.1" -> "I.12";
	# This is for the I.Post.1

	"I.Def.15" -> "I.12";
	# This is for I.Def.15
	"1.7" -> "I.12";
	# This is for 1.7
	
	"I.8" -> "I.12";
	# This is for I.8.
	
	"I.Def.10" -> "I.12";
	# This is for VI.Def.10
	
	
	
	
	
	
	
	
	"VI.8" -> "Proposition 31";
	"I.32" -> "VI.8";
	"VI.4" -> "VI.8";
	"VI.Def.1" -> "VI.8";

	

	
	"VI.Def.1" -> "Proposition 31";
	
	
	"VI.19,Corollary" -> "Proposition 31";
	" V.Def.11" -> "VI.19,Corollary";
	" VI.11" -> "VI.19,Corollary";
	" V.16" -> "VI.19,Corollary";
	" V.11" -> "VI.19,Corollary";
	" VI.15" -> "VI.19,Corollary";
	" V.Def.9" -> "VI.19,Corollary";
	" VI.1" -> "VI.19,Corollary";
	" V.11" -> "VI.19,Corollary";
	" V.7" -> "VI.19,Corollary";







	"V.24" -> "Proposition 31";
	"V.7.Cor" -> "V.24";
	"V.22" -> "V.24";
	"V.18" -> "V.24";
	"V.22" -> "V.24";
    
    	
	
	

}
