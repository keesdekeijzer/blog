# Bestanden voor apt

**/etc/apt/sources.list** : Locaties waarvandaan pakketten opgehaald moeten worden. Configuratie-item: Dir::Etc::SourceList.

**/etc/apt/sources.list.d/** : Bestandsfragmenten met locaties waarvandaan pakketten opgehaald moeten worden. Configuratie-item: Dir::Etc::SourceParts.

**/etc/apt/apt.conf** : Configuratiebestand voor APT. Configuratie-item: Dir::Etc::Main.

**/etc/apt/apt.conf.d/** : Configuratiebestandsfragmenten voor APT. Configuratie-item: Dir::Etc::Parts.

**/etc/apt/preferences** : Bestand met versievoorkeuren. Dit is waar u "pinning" kunt opgeven. Dit is een voorkeur voor het ophalen van bepaalde pakketten uit een aparte pakketbron of uit een andere versie van een distributie. Configuratie-item:
           Dir::Etc::Preferences.
           
**/etc/apt/preferences.d/** : Bestandsfragmenten met versievoorkeuren. Configuratie-item: Dir::Etc::PreferencesParts.

**/var/cache/apt/archives/** : Opslaggebied voor opgehaalde pakketbestanden. Configuratie-item: Dir::Cache::Archives.

**/var/cache/apt/archives/partial/** : Opslaggebied voor pakketbestanden tijdens het ophalen. Configuratie-item: Dir::Cache::Archives (partial zal impliciet toegevoegd worden)

**/var/lib/apt/lists/** : Opslaggebied voor statusinformatie over elke pakketbron vermeld in sources.list(5) Configuratie-item: Dir::State::Lists.

**/var/lib/apt/lists/partial/** : Opslaggebied voor statusinformatie tijdens het ophalen. Configuratie-item: Dir::State::Lists (partial zal impliciet toegevoegd worden)

