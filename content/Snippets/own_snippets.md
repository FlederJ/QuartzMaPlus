
[
	
	// Stuff
	{trigger: "circ", replacement: "\\circ", options: "mA"},
	{trigger: "check", replacement: "\\check{$0}$1", options: "mA"},
	{trigger: "ex", replacement: "\\exists ", options: "m"},
	{trigger: "quad", replacement: "\\quad ", options: "mA"},
	{trigger: "zz", replacement: "\\mathrm{Z\\kern-.3em\\raise-0.5ex\\hbox\{Z\}}: ", options: "mA"},
	
	 // Umlaute
	{trigger: "ä", replacement: "{\\\"a} ", options: "t"},
	{trigger: "ö", replacement: "{\\\"o} ", options: "t"},
	{trigger: "ü", replacement: "{\\\"u} ", options: "t"},

	// Greek Letters
	{trigger: "xi", replacement: "\\xi", options: "mA"},
	{trigger: "eps", replacement: "\\varepsilon", options: "mA"},
	{trigger: "del", replacement: "\\delta", options: "mA"},
	
	
	// Sets and stuff
	{trigger: "KK", replacement: "\\mathbb{K}", options: "mA"},
	{trigger: "QQ", replacement: "\\mathbb{Q}", options: "mA"},
	{trigger: "sup", replacement: "\\sup", options: "mA"},
	{trigger: "inf", replacement: "\\inf", options: "mA"},
	
	// Links
	
	// reelle Zahlen
	{trigger: "Körper ", replacement: "[[Körper]] ", options: "A"},
	{trigger: "geordneter Körper ", replacement: "[[geordneter Körper]] ", options: "A"},
	{trigger: "Supremum ", replacement: "[[Supremum]] ", options: "A"},
	{trigger: "Infimum ", replacement: "[[Infimum]] ", options: "A"},

	{trigger: "Häufungspunkt ", replacement: "[[Häufungspunkt]] ", options: "A"},

	// Folgen
	{trigger:"Folge ", replacement:"[[Folge]] ", options:"A"},
	 {trigger:"konvergent ", replacement:"[[Konvergente Folgen|konvergent]] ", options:"A"},
	 {trigger:"konvergente Folge", replacement:"[[Konvergente Folgen|konvergente Folge]] ", options:"A"},
	 {trigger:"Konvergenz ", replacement:"[[Konvergente Folgen|Konvergenz]] ", options:"A"},
	 {trigger:"beschränkte Folge ", replacement:"[[Beschränkte Folge|beschränkte Folge ]]", options:"A"},
	 {trigger:"monotone Folge ", replacement:"[[Monotone Folgen|monotone Folge ]] ", options:"A"},
	 {trigger:"Teilfolge ", replacement:"[[Teilfolgen|Teilfolge]] ", options:"A"},

	// Stetigkeit etc.
	 {trigger:"stetig ", replacement:"[[Stetigkeit|stetig]] ", options:"A"},
	 {trigger:"kompakt ", replacement:"[[Kompakte Menge|kompakt]] ", options:"A"},
	 {trigger:"offen ", replacement:"[[Offene Menge|offen]] ", options:"A"},
	 {trigger:"abgeschlossen ", replacement:"[[Abgeschlossene Menge|abgeschlossen]] ", options:"A"},
	 
	 {trigger:"gleichmäßig stetig ", replacement:"[[Gleichmäßige Stetigkeit|gleichmäßig stetig]] ", options:"A"},
	 
	 // Differenzierbarkeit
	 {trigger:"differenzierbar ", replacement:"[[Differenzierbarkeit|differenzierbar]] ", options:"A"},
]
