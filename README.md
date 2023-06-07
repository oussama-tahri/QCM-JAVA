<h1 align="center">QCM-JAVA</h1>
<br>

<hr>
<h4> QCM en Java sur divers sujets tels que les flux, les entrées/sorties, les interfaces graphiques, l'accès aux bases de données, le mapping XML, les threads, la programmation réseau et la généricité  + 30 exercices de compilation sur la généricité en Java, avec des solutions détaillées</h4>
<hr>
<br>

## LES FLUX : (LES ENTRÉES ET LES SORTIES)
```markdown
1. Qu'est-ce qu'un flux en Java ?
   - a) Un fichier
   - **b) Un canal de communication entre le programme et les périphériques**
   - c) Une variable utilisée pour stocker des données

2. Quelle classe est utilisée pour lire les données à partir d'un flux d'entrée en Java ?
   - a) BufferedReader
   - b) FileWriter
   - **c) InputStream**

3. Quelle classe est utilisée pour écrire des données dans un flux de sortie en Java ?
   - a) InputStreamReader
   - **b) BufferedWriter**
   - c) OutputStream

4. Quelle méthode est utilisée pour lire une ligne de texte à partir d'un flux d'entrée en Java ?
   - **a) readLine()**
   - b) read()
   - c) nextLine()

5. Quelle méthode est utilisée pour écrire une ligne de texte dans un flux de sortie en Java ?
   - a) writeLine()
   - **b) print()**
   - c) write()

6. Quelle exception doit être gérée lors de l'utilisation des flux en Java ?
   - **a) IOException**
   - b) NullPointerException
   - c) ClassNotFoundException

7. Comment fermer correctement un flux en Java ?
   - a) En appelant la méthode close() sur le flux
   - b) En utilisant le mot-clé "finally"
   - **c) Les deux options précédentes**

8. Quelle méthode est utilisée pour vérifier la disponibilité de données dans un flux d'entrée en Java ?
   - **a) available()**
   - b) hasData()
   - c) hasNext()

9. Quelle classe est utilisée pour lire des données formatées à partir d'un flux d'entrée en Java ?
   - **a) Scanner**
   - b) FileReader
   - c) DataInputStream

10. Quelle méthode est utilisée pour convertir une chaîne de caractères en un type numérique en Java ?
    - **a) parse()**
    - b) toInt()
    - c) convert()

11. Quelle classe est utilisée pour écrire des données formatées dans un flux de sortie en Java ?
    - **a) PrintWriter**
    - b) FileWriter
    - c) ObjectOutputStream

12. Quelle méthode est utilisée pour déplacer le curseur de lecture dans un flux en Java ?
    - **a) seek()**
    - b) moveTo()
    - c) skip()

13. Quelle classe est utilisée pour lire des objets à partir d'un flux d'entrée en Java ?
    - **a) ObjectInputStream**
    - b) FileInputStream
    - c) ObjectReader

14. Quelle méthode est utilisée pour écrire un objet dans un flux de sortie en Java ?
    - **a) writeObject()**
    - b) saveObject()
    - c) serialize()

15. Quelle classe est utilisée pour compresser des données dans un flux de sortie en Java ?
    - **a) GZIPOutputStream**
    - b) ZipOutputStream
    - c) DeflaterOutputStream

16. Quelle méthode est utilisée pour décompresser des données à partir d'un flux d'entrée en Java ?
    - **a) inflate()**
    - b) unzip()
    - c) decompress()

17. Quelle classe est utilisée pour lire des données à partir d'un fichier en Java ?
    - **a) FileReader**
    - b) InputStream
    - c) Scanner

18. Quelle classe est utilisée pour écrire des données dans un fichier en Java ?
    - **a) FileWriter**
    - b) OutputStream
    - c) PrintWriter

19. Quelle méthode est utilisée pour vérifier si un fichier existe en Java ?
    - **a) exists()**
    - b) isFile()
    - c) isDirectory()

20. Quelle classe est utilisée pour créer un nouveau dossier en Java ?
    - **a) File**
    - b) Directory
    - c) Folder

21. Quelle méthode est utilisée pour supprimer un fichier en Java ?
    - **a) delete()**
    - b) remove()
    - c) erase()

22. Quelle classe est utilisée pour lire des données à partir d'une URL en Java ?
    - a) URLReader
    - **b) URLConnection**
    - c) InputStreamReader

23. Quelle méthode est utilisée pour écrire des données dans une URL en Java ?
    - a) writeData()
    - b) sendData()
    - **c) setDoOutput()**

24. Quelle classe est utilisée pour lire des données à partir du clavier en Java ?
    - a) KeyboardReader
    - b) InputStreamReader
    - **c) Scanner**

25. Quelle méthode est utilisée pour vider un flux de sortie en Java ?
    - **a) flush()**
    - b) clear()
    - c) reset()

26. Quelle classe est utilisée pour lire des données à partir d'un tableau de bytes en Java ?
    - a) ByteArrayReader
    - **b) ByteArrayInputStream**
    - c) ByteStreamReader

27. Quelle méthode est utilisée pour écrire des données dans un tableau de bytes en Java ?
    - a) writeBytes()
    - **b) write()**
    - c) toBytes()

28. Quelle classe est utilisée pour lire des données à partir d'un flux en utilisant des tampons en Java ?
    - **a) BufferedInputStream**
    - b) BufferedReader
    - c) BufferStream

29. Quelle méthode est utilisée pour écrire des données dans un flux en utilisant des tampons en Java ?
    - a) writeBytes()
    - b) write()
    - **c) BufferedWriter**

30. Quelle méthode est utilisée pour convertir un flux d'entrée en un flux de caractères en Java ?
    - a) toCharStream()
    - **b) toReader()**
    - c) convertToCharStream()

31. Quelle classe est utilisée pour lire des données à partir d'un flux en utilisant des objets sérialisés en Java ?
    - **a) ObjectInputStream**
    - b) ObjectReader
    - c) SerializedInputStream

32. Quelle méthode est utilisée pour écrire des données dans un flux en utilisant des objets sérialisés en Java ?
    - a) writeSerialized()
    - **b) writeObject()**
    - c) serialize()

33. Quelle méthode est utilisée pour écrire des données dans un flux de sortie en utilisant l'encodage UTF-8 en Java ?
    - a) writeUTF8()
    - **b) write()**
    - c) writeEncoded()

34. Quelle classe est utilisée pour lire des données à partir d'un fichier compressé en Java ?
    - a) CompressedReader
    - **b) GZIPInputStream**
    - c) ZipReader

35. Quelle classe est utilisée pour écrire des données dans un fichier compressé en Java ?
    - a) CompressedWriter
    - **b) GZIPOutputStream**
    - c) ZipWriter

36. Quelle méthode est utilisée pour déplacer le curseur de lecture dans un fichier en Java ?
    - **a) seek()**
    - b) moveTo()
    - c) skip()

37. Quelle classe est utilisée pour lire des données à partir d'une connexion réseau en Java ?
    - a) SocketReader
    - **b) InputStream**
    - c) InputStreamReader

38. Quelle classe est utilisée pour écrire des données dans une connexion réseau en Java ?
    - a) SocketWriter
    - **b) OutputStream**
    - c) OutputStreamWriter

39. Quelle méthode est utilisée pour changer le mode d'ouverture d'un fichier en Java ?
    - a) setMode()
    - b) changeMode()
    - **c) setWritable()**

40. Quelle classe est utilisée pour lire des données à partir d'un flux de données binaires en Java ?
    - **a) DataInputStream**
    - b) BinaryReader
    - c) InputStream

41. Quelle classe est utilisée pour écrire des données dans un flux de données binaires en Java ?
    - **a) DataOutputStream**
    - b) BinaryWriter
    - c) OutputStream

42. Quelle méthode est utilisée pour vérifier si un fichier est accessible en lecture en Java ?
    - a) isReadable()
    - **b) canRead()**
    - c) isFileAccessible()

43. Quelle méthode est utilisée pour vérifier si un fichier est accessible en écriture en Java ?
    - a) isWritable()
    - **b) canWrite()**
    - c) isFileWritable()

44. Quelle classe est utilisée pour lire des données à partir d'un flux de caractères en Java ?
    - a) CharacterReader
    - b) InputStreamReader
    - **c) BufferedReader**

45. Quelle méthode est utilisée pour écrire des données dans un flux de caractères en Java ?
    - a) writeChars()
    - b) write()
    - **c) BufferedWriter**

46. Quelle méthode est utilisée pour vérifier si un fichier est exécutable en Java ?
    - a) isExecutable()
    - **b) canExecute()**
    - c) isFileExecutable()

47. Quelle méthode est utilisée pour obtenir la taille d'un fichier en Java ?
    - a) size()
    - **b) length()**
    - c) getSize()

48. Quelle classe est utilisée pour écrire des données dans un fichier texte en Java ?
    - a) TextFileWriter
    - **b) FileWriter**
    - c) OutputStreamWriter

49. Quelle méthode est utilisée pour convertir un flux d'entrée en un flux de caractères en utilisant un encodage spécifié en Java ?
    - a) toCharStream()
    - **b) toReader()**
    - c) InputStreamReader

50. Quelle méthode est utilisée pour convertir un flux de sortie en un flux de caractères en utilisant un encodage spécifié en Java ?
    - a) toCharStream()
    - **b) toWriter()**
    - c) OutputStreamWriter
```

<br>

## INTERFACES GRAPHIQUES EN JAVAFX :
```markdown

1. Qu'est-ce que JavaFX ?
   - a) Une bibliothèque de développement pour les jeux vidéo en Java
   - **b) Un framework pour créer des interfaces graphiques en Java**
   - c) Une méthode pour manipuler des fichiers XML en Java

2. Quelle est la classe principale pour démarrer une application JavaFX ?
   - **a) Application**
   - b) Main
   - c) Window

3. Quel est le package de base pour les classes JavaFX ?
   - a) java.util
   - **b) javafx**
   - c) java.awt

4. Quelle classe est utilisée pour représenter une fenêtre dans JavaFX ?
   - **a) Stage**
   - b) Window
   - c) Frame

5. Quelle classe est utilisée pour organiser les éléments graphiques en JavaFX ?
   - a) LayoutPane
   - **b) Pane**
   - c) Panel

6. Quelle classe est utilisée pour afficher du texte dans JavaFX ?
   - **a) Label**
   - b) Text
   - c) TextView

7. Quelle classe est utilisée pour créer des boutons dans JavaFX ?
   - **a) Button**
   - b) Clickable
   - c) Control

8. Quelle classe est utilisée pour créer des cases à cocher dans JavaFX ?
   - a) CheckButton
   - b) Checkbox
   - **c) CheckBox**

9. Quelle classe est utilisée pour créer des zones de saisie de texte dans JavaFX ?
   - a) TextField
   - **b) TextInput**
   - c) InputBox

10. Quelle classe est utilisée pour créer des menus déroulants dans JavaFX ?
    - **a) ComboBox**
    - b) DropdownMenu
    - c) MenuBar

11. Quelle classe est utilisée pour créer des listes déroulantes dans JavaFX ?
    - a) SelectList
    - **b) ChoiceBox**
    - c) DropdownList

12. Quelle classe est utilisée pour afficher des images dans JavaFX ?
    - a) ImageBox
    - **b) ImageView**
    - c) PictureView

13. Quelle classe est utilisée pour créer des tableaux de données dans JavaFX ?
    - a) DataTable
    - b) GridPane
    - **c) TableView**

14. Quelle classe est utilisée pour créer des onglets dans JavaFX ?
    - a) PanelTab
    - b) TabView
    - **c) TabPane**

15. Quelle classe est utilisée pour créer des boîtes de dialogue dans JavaFX ?
    - a) MessageDialog
    - b) PopUpBox
    - **c) Alert**

16. Quelle classe est utilisée pour créer des barres de progression dans JavaFX ?
    - **a) ProgressBar**
    - b) ProgressIndicator
    - c) LoadingBar

17. Quelle classe est utilisée pour créer des fenêtres modales dans JavaFX ?
    - a) ModalWindow
    - **b) Dialog**
    - c) PopupWindow

18. Quelle classe est utilisée pour créer des fenêtres de sélection de fichiers dans JavaFX ?
    - a) FilePicker
    - b) FileSelector
    - **c) FileChooser**

19. Quelle classe est utilisée pour créer des animations dans JavaFX ?
    - **a) Animation**
    - b) Tween
    - c) Transition

20. Quelle classe est utilisée pour créer des effets visuels dans JavaFX ?
    - a) VisualEffect
    - **b) Effect**
    - c) GraphicEffect

21. Quelle classe est utilisée pour créer des formes géométriques dans JavaFX ?
    - a) GeometricShape
    - **b) Shape**
    - c) Polygon

22. Quelle classe est utilisée pour gérer les événements de souris dans JavaFX ?
    - **a) MouseEvent**
    - b) ClickEvent
    - c) MouseAdapter

23. Quelle classe est utilisée pour gérer les événements de clavier dans JavaFX ?
    - a) KeyboardEvent
    - **b) KeyEvent**
    - c) KeyAdapter

24. Quelle classe est utilisée pour gérer les événements de focus dans JavaFX ?
    - a) FocusEvent
    - **b) FocusEvent**
    - c) FocusAdapter

25. Quelle classe est utilisée pour gérer les événements de scroll dans JavaFX ?
    - **a) ScrollEvent**
    - b) ScrollAdapter
    - c) ScrollListener

26. Quelle classe est utilisée pour gérer les événements de drag-and-drop dans JavaFX ?
    - **a) DragEvent**
    - b) DropEvent
    - c) DragDropEvent

27. Quelle classe est utilisée pour appliquer des styles CSS à des éléments graphiques dans JavaFX ?
    - a) CSSStyle
    - **b) Style**
    - c) CSSClass

28. Quelle classe est utilisée pour gérer les transitions d'animation dans JavaFX ?
    - **a) Transition**
    - b) Animation
    - c) Tween

29. Quelle classe est utilisée pour afficher des notifications dans JavaFX ?
    - a) MessageNotification
    - **b) Notification**
    - c) AlertBox

30. Quelle classe est utilisée pour créer des graphiques et des diagrammes dans JavaFX ?
    - **a) Chart**
    - b) Graph
    - c) Diagram

31. Quelle classe est utilisée pour créer des zones de dessin personnalisées dans JavaFX ?
    - a) CustomPane
    - b) DrawingArea
    - **c) Canvas**

32. Quelle classe est utilisée pour créer des menus contextuels dans JavaFX ?
    - a) PopupMenu
    - **b) ContextMenu**
    - c) RightClickMenu

33. Quelle classe est utilisée pour créer des barres de menus dans JavaFX ?
    - **a) MenuBar**
    - b) MenuBarView
    - c) TopMenu

34. Quelle classe est utilisée pour créer des barres d'outils dans JavaFX ?
    - a) ToolPanel
    - **b) ToolBar**
    - c) ActionBar

35. Quelle classe est utilisée pour créer des curseurs personnalisés dans JavaFX ?
    - a) CustomCursor
    - b) MouseCursor
    - **c) Cursor**

36. Quelle classe est utilisée pour créer des zones de texte éditable dans JavaFX ?
    - a) EditableText
    - **b) TextField**
    - c) EditField

37. Quelle classe est utilisée pour créer des zones de texte multiligne dans JavaFX ?
    - a) TextArea
    - b) TextEditor
    - **c) TextArea**

38. Quelle classe est utilisée pour créer des boutons radio dans JavaFX ?
    - a) RadioButton
    - **b) ToggleButton**
    - c) RadioControl

39. Quelle classe est utilisée pour créer des sélecteurs de date dans JavaFX ?
    - a) DateSelector
    - **b) DatePicker**
    - c) DateChooser

40. Quelle classe est utilisée pour créer des sélecteurs de couleur dans JavaFX ?
    - a) ColorSelector
    - **b) ColorPicker**
    - c) ColorChooser

41. Quelle classe est utilisée pour créer des séparateurs visuels dans JavaFX ?
    - a) Separator
    - **b) Separator**
    - c) Divider

42. Quelle classe est utilisée pour créer des indicateurs de progression circulaires dans JavaFX ?
    - **a) ProgressIndicator**
    - b) CircularProgress
    - c) LoadingIndicator

43. Quelle classe est utilisée pour créer des graphiques à secteurs dans JavaFX ?
    - a) PieChart
    - **b) PieChart**
    - c) SectorChart

44. Quelle classe est utilisée pour créer des graphiques en barres dans JavaFX ?
    - a) BarChart
    - **b) BarChart**
    - c) ColumnChart

45. Quelle classe est utilisée pour créer des graphiques en courbes dans JavaFX ?
    - a) LineChart
    - **b) LineChart**
    - c) CurveChart

46. Quelle classe est utilisée pour créer des graphiques en aires dans JavaFX ?
    - a) AreaChart
    - **b) AreaChart**
    - c) FillChart

47. Quelle classe est utilisée pour créer des graphiques en nuages de points dans JavaFX ?
    - **a) ScatterChart**
    - b) PointChart
    - c) DotChart

48. Quelle classe est utilisée pour créer des graphiques en radar dans JavaFX ?
    - a) SpiderChart
    - b) RadarChart
    - **c) PolarChart**

49. Quelle classe est utilisée pour créer des graphiques en bulles dans JavaFX ?
    - a) BubbleChart
    - **b) BubbleChart**
    - c) BalloonChart

50. Quelle classe est utilisée pour créer des graphiques en aires empilées dans JavaFX ?
    - a) StackedChart
    - b) AreaStackChart
    - **c) StackedAreaChart**
```
<br>

## ACCÈS AUX BASES DE DONNÉES :
```markdown

1. Quelle API est utilisée pour accéder aux bases de données relationnelles en Java ?
   - a) JDBC
   - **b) SQL**
   - c) JPA

2. Quelle classe est utilisée pour établir une connexion à une base de données en Java ?
   - **a) Connection**
   - b) Database
   - c) Connector

3. Quelle interface est utilisée pour exécuter des requêtes SQL en Java ?
   - a) QueryExecutor
   - **b) Statement**
   - c) QueryRunner

4. Quelle interface est utilisée pour exécuter des requêtes SQL paramétrées en Java ?
   - a) ParametricStatement
   - **b) PreparedStatement**
   - c) QueryBuilder

5. Quelle interface est utilisée pour récupérer les résultats d'une requête SQL en Java ?
   - **a) ResultSet**
   - b) QueryResult
   - c) ResultCollector

6. Quelle classe est utilisée pour représenter les métadonnées d'une table dans une base de données en Java ?
   - **a) ResultSetMetaData**
   - b) DatabaseMetaData
   - c) TableMetaData

7. Quelle méthode est utilisée pour exécuter une requête de mise à jour (INSERT, UPDATE, DELETE) en Java ?
   - a) executeQuery()
   - **b) executeUpdate()**
   - c) executeModification()

8. Quelle méthode est utilisée pour exécuter une requête de sélection (SELECT) en Java ?
   - **a) executeQuery()**
   - b) executeSelect()
   - c) executeRetrieve()

9. Quelle méthode est utilisée pour exécuter une requête SQL paramétrée en Java ?
   - **a) setXXX()**
   - b) bindXXX()
   - c) parameterXXX()

10. Quelle méthode est utilisée pour récupérer les résultats d'une requête SELECT en Java ?
    - a) getResults()
    - **b) getResultSet()**
    - c) fetchResults()

11. Quelle méthode est utilisée pour déplacer le curseur de résultats dans un ResultSet en Java ?
    - a) nextRow()
    - **b) next()**
    - c) moveToNext()

12. Quelle méthode est utilisée pour récupérer la valeur d'une colonne dans un ResultSet en Java ?
    - a) getColumnValue()
    - **b) getString()**
    - c) getValue()

13. Quelle méthode est utilisée pour fermer une connexion à une base de données en Java ?
    - **a) close()**
    - b) disconnect()
    - c) shutdown()

14. Quelle classe est utilisée pour gérer les exceptions liées à l'accès aux bases de données en Java ?
    - a) SQLExceptionHandler
    - **b) SQLException**
    - c) DatabaseException

15. Quelle classe est utilisée pour représenter une base de données en Java ?
    - a) Database
    - **b) Connection**
    - c) DataSource

16. Quelle classe est utilisée pour gérer les transactions en Java ?
    - a) TransactionManager
    - **b) Connection**
    - c) TransactionHandler

17. Quelle interface est utilisée pour créer des requêtes SQL de manière fluide en Java ?
    - a) QueryBuilder
    - **b) PreparedStatement**
    - c) StatementBuilder

18. Quelle méthode est utilisée pour récupérer la dernière valeur générée par une séquence dans une base de données en Java ?
    - a) getLastValue()
    - **b) getGeneratedKeys()**
    - c) fetchLastGenerated()

19. Quelle méthode est utilisée pour exécuter une procédure stockée en Java ?
    - a) executeQuery()
    - b) executeProcedure()
    - **c) CallableStatement**

20. Quelle méthode est utilisée pour exécuter un lot de requêtes en Java ?
    - a) executeBatch()
    - **b) execute()
    - c) executeAll()

21. Quelle méthode est utilisée pour effectuer un commit d'une transaction en Java ?
    - a) endTransaction()
    - **b) commit()**
    - c) finishTransaction()

22. Quelle méthode est utilisée pour effectuer un rollback d'une transaction en Java ?
    - a) rollbackTransaction()
    - **b) rollback()**
    - c) cancelTransaction()

23. Quelle méthode est utilisée pour définir un point de sauvegarde (savepoint) dans une transaction en Java ?
    - a) setSavepoint()
    - **b) setSavepoint(String savepointName)**
    - c) createSavepoint()

24. Quelle méthode est utilisée pour annuler un point de sauvegarde (savepoint) dans une transaction en Java ?
    - a) cancelSavepoint()
    - **b) releaseSavepoint()**
    - c) removeSavepoint()

25. Quelle méthode est utilisée pour effectuer une opération d'agrégation (SUM, COUNT, AVG) dans une requête SQL en Java ?
    - **a) SELECT SUM(column) FROM table**
    - b) SELECT COLUMN_SUM(column) FROM table
    - c) SELECT COUNT(column) FROM table

26. Quelle méthode est utilisée pour effectuer une jointure (JOIN) de tables dans une requête SQL en Java ?
    - a) SELECT * FROM table1 WHERE table1.id = table2.id
    - b) SELECT * FROM table1.table2
    - **c) SELECT * FROM table1 INNER JOIN table2 ON table1.id = table2.id**

27. Quelle méthode est utilisée pour trier les résultats d'une requête SQL en Java ?
    - a) SELECT * FROM table ORDER BY column
    - **b) SELECT * FROM table ORDER BY column ASC**
    - c) SELECT * FROM table SORT BY column

28. Quelle méthode est utilisée pour filtrer les résultats d'une requête SQL en Java ?
    - a) SELECT * FROM table FILTER column = value
    - **b) SELECT * FROM table WHERE column = value**
    - c) SELECT * FROM table HAVING column = value

29. Quelle méthode est utilisée pour paginer les résultats d'une requête SQL en Java ?
    - a) SELECT * FROM table LIMIT start, end
    - **b) SELECT * FROM table LIMIT offset, count**
    - c) SELECT * FROM table RANGE start, end

30. Quelle méthode est utilisée pour exécuter une requête SQL stockée dans un fichier en Java ?
    - **a) Utiliser un objet PreparedStatement avec la requête SQL**
    - b) Utiliser un objet Statement avec la requête SQL
    - c) Utiliser un objet CallableStatement avec la requête SQL

31. Quelle méthode est utilisée pour exécuter une requête SQL asynchrone en Java ?
    - a) executeQueryAsync()
    - **b) executeAsync()**
    - c) executeNonBlocking()

32. Quelle classe est utilisée pour gérer les pool de connexions en Java ?
    - a) ConnectionManager
    - **b) DataSource**
    - c) ConnectionPool

33. Quelle classe est utilisée pour effectuer des opérations transactionnelles en Java ?
    - a) TransactionExecutor
    - **b) TransactionManager**
    - c) TransactionHandler

34. Quelle méthode est utilisée pour exécuter une requête SQL avec des paramètres nommés en Java ?
    - a) setParameters()
    - **b) setString(String parameterName, String value)**
    - c) bindParameter()

35. Quelle classe est utilisée pour mapper les résultats d'une requête SQL à des objets en Java ?
    - a) ResultSetMapper
    - **b) ObjectMapper**
    - c) EntityMapper

36. Quelle méthode est utilisée pour insérer des données dans une base de données en Java ?
    - a) insertRow()
    - **b) executeInsert()**
    - c) addData()

37. Quelle méthode est utilisée pour mettre à jour des données dans une base de données en Java ?
    - a) updateData()
    - **b) executeUpdate()**
    - c) modifyRow()

38. Quelle méthode est utilisée pour supprimer des données dans une base de données en Java ?
    - a) removeRow()
    - **b) executeDelete()**
    - c) deleteData()

39. Quelle classe est utilisée pour représenter un enregistrement (row) dans une base de données en Java ?
    - a) DataRow
    - **b) ResultSet**
    - c) Record

40. Quelle méthode est utilisée pour récupérer le nombre d'enregistrements affectés par une requête en Java ?
    - a) getAffectedRows()
    - **b) getUpdateCount()**
    - c) fetchAffectedRows()

41. Quelle méthode est utilisée pour définir le niveau d'isolation d'une transaction en Java ?
    - a) setTransactionIsolationLevel()
    - **b) setTransactionIsolation(int level)**
    - c) setTransactionLevel()

42. Quelle méthode est utilisée pour définir le temps limite (timeout) d'une requête en Java ?
    - a) setQueryTimeout()
    - **b) setQueryTimeout(int seconds)**
    - c) setTimeout()

43. Quelle méthode est utilisée pour définir le mode de validation d'une transaction en Java ?
    - a) setTransactionValidation()
    - **b) setAutoCommit(boolean autoCommit)**
    - c) setValidationMode()

44. Quelle méthode est utilisée pour définir le mode de fermeture de la connexion à une base de données en Java ?
    - a) setCloseMode()
    - **b) setAutoClose(boolean autoClose)**
    - c) setConnectionClosing()

45. Quelle méthode est utilisée pour gérer les exceptions liées à la fermeture de ressources en Java ?
    - a) ResourceException
    - **b) IOException**
    - c) CloseException

46. Quelle méthode est utilisée pour définir le mode de lecture seule d'une connexion à une base de données en Java ?
    - a) setReadOnlyMode()
    - **b) setReadOnly(boolean readOnly)**
    - c) setAccessMode()

47. Quelle méthode est utilisée pour définir le niveau de journalisation (logging) d'une connexion à une base de données en Java ?
    - a) setLogMode()
    - **b) setLogLevel(int level)**
    - c) setLoggingLevel()

48. Quelle méthode est utilisée pour définir le nombre maximum de lignes retournées par une requête en Java ?
    - a) setMaxRows()
    - **b) setMaxResults(int max)**
    - c) setLimit()

49. Quelle méthode est utilisée pour définir le comportement de mise à jour des résultats d'une requête en Java ?
    - **a) setConcurrencyMode()**
    - b) setUpdateMode()
    - c) setResultSetConcurrency()

50. Quelle méthode est utilisée pour définir le comportement de défilement des résultats d'une requête en Java ?
    - a) setScrollMode()
    - **b) setFetchSize(int rows)**
    - c) setResultSetScrollability()
```
<br>

## MAPPING OBJET XML (OXM) | JAX BINDING (JAXB2) :
```markdown

1. Qu'est-ce que le MAPPING OBJET XML (OXM) en Java ?
   - a) Une technique de compression de fichiers XML
   - **b) Une technique de transformation de données entre des objets Java et des documents XML**
   - c) Une technique de cryptage des données XML

2. Qu'est-ce que JAX BINDING (JAXB2) en Java ?
   - a) Un framework pour la création d'interfaces graphiques en Java
   - **b) Un framework pour la conversion entre des classes Java et des documents XML**
   - c) Un framework pour l'accès aux bases de données en Java

3. Quelle API est utilisée pour le MAPPING OBJET XML (OXM) en Java ?
   - **a) JAXB (Java Architecture for XML Binding)**
   - b) JAX-WS (Java API for XML Web Services)
   - c) JAX-RS (Java API for RESTful Web Services)

4. Comment peut-on représenter une classe Java sous forme de document XML à l'aide de JAXB ?
   - a) En utilisant la classe XmlSerializer
   - **b) En annotant la classe Java avec des annotations JAXB**
   - c) En utilisant la classe XmlMapper

5. Comment peut-on représenter un document XML sous forme de classe Java à l'aide de JAXB ?
   - a) En utilisant la classe XmlDeserializer
   - **b) En générant des classes Java à partir du schéma XML (XSD) à l'aide de JAXB**
   - c) En utilisant la classe XmlMapper

6. Quelle annotation est utilisée pour marquer une classe Java en tant qu'élément racine d'un document XML avec JAXB ?
   - a) @XmlElement
   - **b) @XmlRootElement**
   - c) @XmlAccessorType

7. Quelle annotation est utilisée pour marquer un champ ou une méthode Java en tant qu'élément XML avec JAXB ?
   - **a) @XmlElement**
   - b) @XmlRootElement
   - c) @XmlAccessorType

8. Quelle annotation est utilisée pour spécifier le nom d'un élément XML avec JAXB ?
   - a) @XmlName
   - **b) @XmlElement(name = "elementName")**
   - c) @XmlRootElement(name = "elementName")

9. Quelle annotation est utilisée pour spécifier l'ordre des éléments XML dans une classe Java avec JAXB ?
   - a) @XmlOrder
   - **b) @XmlType(propOrder = {"element1", "element2"})**
   - c) @XmlSequence

10. Quelle annotation est utilisée pour ignorer un champ ou une méthode Java lors de la conversion en XML avec JAXB ?
    - **a) @XmlTransient**
    - b) @XmlIgnore
    - c) @XmlExclude

11. Quelle annotation est utilisée pour spécifier le type de données d'un élément XML avec JAXB ?
    - **a) @XmlType**
    - b) @XmlSchema
    - c) @XmlDataType

12. Quelle annotation est utilisée pour spécifier le format de date et d'heure d'un élément XML avec JAXB ?
    - **a) @XmlJavaTypeAdapter**
    - b) @XmlDateTimeFormat
    - c) @XmlDateFormat

13. Quelle annotation est utilisée pour spécifier la cardinalité d'un élément XML avec JAXB ?
    - a) @XmlElementCardinality
    - **b) @XmlElementWrapper**
    - c) @XmlCardinality

14. Quelle annotation est utilisée pour spécifier la valeur par défaut d'un élément XML avec JAXB ?
    - a) @XmlDefaultValue
    - **b) @XmlValue**
    - c) @XmlDefault

15. Quelle annotation est utilisée pour spécifier une référence à un autre élément XML avec JAXB ?
    - a) @XmlReference
    - **b) @XmlIDREF**
    - c) @XmlLink

16. Comment peut-on générer des classes Java à partir d'un schéma XML (XSD) à l'aide de JAXB ?
    - a) En utilisant l'outil xml2java
    - **b) En utilisant le compilateur xjc (XJC - XML to Java Compiler) fourni avec JAXB**
    - c) En utilisant l'API Java Reflection

17. Quelle classe est utilisée pour effectuer la conversion entre des objets Java et des documents XML avec JAXB ?
    - **a) JAXBContext**
    - b) XmlConverter
    - c) XmlBinder

18. Quelle méthode est utilisée pour marquer un objet Java en tant que document XML racine avec JAXB ?
    - a) createRootElement()
    - **b) createMarshaller()**
    - c) createDocument()

19. Quelle méthode est utilisée pour marquer un document XML en tant qu'objet Java avec JAXB ?
    - **a) createUnmarshaller()**
    - b) createObjectMapper()
    - c) createBinder()

20. Quelle méthode est utilisée pour convertir un objet Java en document XML avec JAXB ?
    - **a) marshal()**
    - b) serialize()
    - c) convert()

21. Quelle méthode est utilisée pour convertir un document XML en objet Java avec JAXB ?
    - **a) unmarshal()**
    - b) deserialize()
    - c) convert()

22. Quelle méthode est utilisée pour valider un document XML par rapport à un schéma XML (XSD) avec JAXB ?
    - **a) setSchema()**
    - b) validateSchema()
    - c) enableValidation()

23. Quelle méthode est utilisée pour générer un schéma XML (XSD) à partir de classes Java avec JAXB ?
    - a) generateSchema()
    - **b) generateXSD()**
    - c) createSchema()

24. Quelle classe est utilisée pour représenter un schéma XML (XSD) avec JAXB ?
    - a) XmlSchema
    - **b) Schema**
    - c) XsdSchema

25. Quelle méthode est utilisée pour spécifier un espace de noms par défaut pour les éléments XML avec JAXB ?
    - **a) @XmlSchema(namespace = "namespaceURI")**
    - b) @XmlNamespace
    - c) @XmlNamespaceDefault

26. Comment peut-on spécifier un espace de noms pour un élément XML avec JAXB ?
    - a) En utilisant l'annotation @XmlSchema
    - **b) En utilisant l'annotation @XmlElement(namespace = "namespaceURI")**
    - c) En utilisant l'annotation @XmlNamespace

27. Quelle annotation est utilisée pour spécifier une référence cyclique entre des objets Java avec JAXB ?
    - a) @XmlReference
    - **b) @XmlID/@XmlIDREF**
    - c) @XmlCycle

28. Quelle annotation est utilisée pour spécifier une classe de conversion personnalisée pour un élément XML avec JAXB ?
    - a) @XmlConversion
    - **b) @XmlJavaTypeAdapter**
    - c) @XmlCustomConverter

29. Quelle classe est utilisée pour spécifier des règles de validation personnalisées pour un élément XML avec JAXB ?
    - **a) Validator**
    - b) XmlValidator
    - c) XmlValidationRules

30. Quelle méthode est utilisée pour spécifier un validateur personnalisé pour la validation des documents XML avec JAXB ?
    - **a) setValidator()**
    - b) validateWith()
    - c) enableCustomValidation()

31. Quelle annotation est utilisée pour spécifier un commentaire XML pour un élément avec JAXB ?
    - a) @XmlComment
    - **b) @XmlJavaTypeAdapter(XmlCommentAdapter.class)**
    - c) @XmlValueComment

32. Quelle annotation est utilisée pour spécifier la présence optionnelle d'un élément XML avec JAXB ?
    - a) @XmlRequired
    - **b) @XmlElement(required = false)**
    - c) @XmlOptional

33. Quelle annotation est utilisée pour spécifier la version d'un élément XML avec JAXB ?
    - **a) @XmlSchemaVersion**
    - b) @XmlVersion
    - c) @XmlRootElement(version = "1.0")

34. Quelle annotation est utilisée pour spécifier la localisation d'un élément XML avec JAXB ?
    - a) @XmlLocation
    - **b) @XmlPath**
    - c) @XmlElementLocation

35. Quelle méthode est utilisée pour spécifier l'encodage d'un document XML avec JAXB ?
    - a) setEncoding()
    - **b) setProperty(Marshaller.JAXB_ENCODING, "encoding")**
    - c) setXmlEncoding()

36. Quelle méthode est utilisée pour spécifier le formatage d'un document XML avec JAXB ?
    - **a) setProperty(Marshaller.JAXB_FORMATTED_OUTPUT, true)**
    - b) setFormattedOutput()
    - c) setXmlFormatting()

37. Quelle méthode est utilisée pour spécifier l'indentation d'un document XML avec JAXB ?
    - a) setIndentation()
    - **b) setProperty(Marshaller.JAXB_FORMATTED_OUTPUT, true)**
    - c) setXmlIndentation()

38. Quelle méthode est utilisée pour spécifier la gestion des espaces de noms par défaut avec JAXB ?
    - **a) setProperty(Marshaller.JAXB_FRAGMENT, true)**
    - b) setNamespaceHandling()
    - c) setXmlNamespaceDefault()

39. Quelle méthode est utilisée pour spécifier la gestion des déclarations de préfixes d'espaces de noms avec JAXB ?
    - a) setNamespacePrefixes()
    - **b) setProperty(Marshaller.JAXB_FRAGMENT, true)**
    - c) setXmlNamespacePrefixes()

40. Quelle méthode est utilisée pour spécifier la gestion des caractères spéciaux dans un document XML avec JAXB ?
    - a) setCharacterHandling()
    - **b) setProperty(Marshaller.JAXB_FRAGMENT, true)**
    - c) setXmlCharacterHandling()

41. Quelle classe est utilisée pour effectuer la validation d'un document XML avec JAXB ?
    - a) XmlValidator
    - **b) Validator**
    - c) XmlSchemaValidator

42. Quelle méthode est utilisée pour récupérer les erreurs de validation lors de la validation d'un document XML avec JAXB ?
    - **a) getValidationErrors()**
    - b) getErrors()
    - c) getValidationMessages()

43. Quelle méthode est utilisée pour ignorer les erreurs de validation lors de la validation d'un document XML avec JAXB ?
    - a) ignoreValidationErrors()
    - **b) setEventHandler(null)**
    - c) disableValidation()

44. Quelle méthode est utilisée pour spécifier la résolution des entités externes lors de la validation d'un document XML avec JAXB ?
    - a) setEntityResolution()
    - **b) setProperty(Marshaller.JAXB_NO_NAMESPACE_SCHEMA_LOCATION, true)**
    - c) setXmlEntityResolution()

45. Quelle méthode est utilisée pour spécifier la gestion des erreurs lors de la validation d'un document XML avec JAXB ?
    - **a) setEventHandler(ValidationEventHandler handler)**
    - b) setErrorHandling()
    - c) setXmlErrorHandling()

46. Quelle méthode est utilisée pour spécifier la gestion des avertissements lors de la validation d'un document XML avec JAXB ?
    - a) setWarningHandling()
    - **b) setEventHandler(ValidationEventHandler handler)**
    - c) setXmlWarningHandling()

47. Quelle méthode est utilisée pour spécifier la gestion des erreurs fatales lors de la validation d'un document XML avec JAXB ?
    - a) setFatalErrorHandling()
    - **b) setEventHandler(ValidationEventHandler handler)**
    - c) setXmlFatalErrorHandling()

48. Quelle méthode est utilisée pour spécifier la gestion des erreurs lors de la conversion entre des objets Java et des documents XML avec JAXB ?
    - a) setErrorHandling()
    - **b) setEventHandler(ValidationEventHandler handler)**
    - c) setXmlErrorHandling()

49. Quelle méthode est utilisée pour spécifier la gestion des avertissements lors de la conversion entre des objets Java et des documents XML avec JAXB ?
    - a) setWarningHandling()
    - **b) setEventHandler(ValidationEventHandler handler)**
    - c) setXmlWarningHandling()

50. Quelle méthode est utilisée pour spécifier la gestion des erreurs fatales lors de la conversion entre des objets Java et des documents XML avec JAXB ?
    - a) setFatalErrorHandling()
    - **b) setEventHandler(ValidationEventHandler handler)**
    - c) setXmlFatalErrorHandling()
```
<br>

## LES THREADS EN JAVA :
```markdown

1. Qu'est-ce qu'un thread en Java ?
   - a) Un type de variable
   - **b) Un flux d'exécution indépendant**
   - c) Une classe Java

2. Comment peut-on créer un thread en Java ?
   - a) En instanciant la classe Thread
   - **b) En étendant la classe Thread**
   - c) En utilisant une interface Runnable

3. Quelle méthode est utilisée pour démarrer l'exécution d'un thread en Java ?
   - a) start()
   - **b) run()**
   - c) execute()

4. Quelle méthode est utilisée pour arrêter l'exécution d'un thread en Java ?
   - a) stop()
   - **b) interrupt()**
   - c) end()

5. Comment peut-on mettre en pause l'exécution d'un thread en Java ?
   - **a) En utilisant la méthode sleep()**
   - b) En utilisant la méthode pause()
   - c) En utilisant la méthode wait()

6. Quelle méthode est utilisée pour obtenir l'état d'un thread en Java ?
   - a) state()
   - **b) getState()**
   - c) getStatus()

7. Comment peut-on définir une priorité pour l'exécution d'un thread en Java ?
   - **a) En utilisant la méthode setPriority()**
   - b) En utilisant la méthode setThreadPriority()
   - c) En utilisant la méthode setExecutionPriority()

8. Quelle est la priorité par défaut d'un thread en Java ?
   - a) Haute (High)
   - **b) Normale (Normal)**
   - c) Basse (Low)

9. Quelle est la priorité maximale d'un thread en Java ?
   - a) 10
   - **b) Thread.MAX_PRIORITY**
   - c) 100

10. Quelle est la priorité minimale d'un thread en Java ?
    - **a) Thread.MIN_PRIORITY**
    - b) 1
    - c) Bas (Low)

11. Comment peut-on attendre la fin d'exécution d'un thread en Java ?
    - a) En utilisant la méthode wait()
    - **b) En utilisant la méthode join()**
    - c) En utilisant la méthode stop()

12. Quelle méthode est utilisée pour vérifier si un thread est en cours d'exécution en Java ?
    - a) isAlive()
    - **b) isRunning()**
    - c) isExecuting()

13. Comment peut-on partager des données entre plusieurs threads en Java ?
    - a) En utilisant des variables locales
    - **b) En utilisant des variables partagées synchronisées**
    - c) En utilisant des variables globales

14. Quelle classe est utilisée pour synchroniser l'accès à un bloc de code en Java ?
    - a) SyncLock
    - **b) ReentrantLock**
    - c) ThreadSync

15. Comment peut-on synchroniser l'accès à une méthode en Java ?
    - a) En utilisant la classe SyncMethod
    - **b) En utilisant le mot-clé synchronized**
    - c) En utilisant le mot-clé sync

16. Quelle méthode est utilisée pour bloquer l'accès concurrent à un bloc de code en Java ?
    - a) lock()
    - **b) synchronized**
    - c) block()

17. Comment peut-on éviter les conditions de concurrence en Java ?
    - a) En utilisant des threads indépendants
    - **b) En utilisant des mécanismes de synchronisation**
    - c) En utilisant des threads avec des priorités différentes

18. Quelle est la différence entre un thread et un processus en Java ?
    - a) Un thread est un sous-processus d'un processus
    - **b) Un processus est une instance d'un programme en cours d'exécution, tandis qu'un thread est un flux d'exécution dans un processus**
    - c) Un processus est géré par le système d'exploitation, tandis qu'un thread est géré par le compilateur Java

19. Quelle méthode est utilisée pour mettre en attente un thread en Java ?
    - a) sleep()
    - **b) wait()**
    - c) pause()

20. Quelle méthode est utilisée pour reprendre l'exécution d'un thread en attente en Java ?
    - a) resume()
    - **b) notify()**
    - c) resumeExecution()

21. Comment peut-on créer un pool de threads en Java ?
    - **a) En utilisant la classe ExecutorService**
    - b) En utilisant la classe ThreadPool
    - c) En utilisant la classe ThreadManager

22. Quelle méthode est utilisée pour soumettre une tâche à un pool de threads en Java ?
    - a) executeTask()
    - **b) submit()**
    - c) addTask()

23. Comment peut-on arrêter l'exécution d'un pool de threads en Java ?
    - **a) En utilisant la méthode shutdown()**
    - b) En utilisant la méthode stop()
    - c) En utilisant la méthode end()

24. Quelle est la différence entre un pool de threads fixe et un pool de threads extensible en Java ?
    - a) Un pool de threads fixe a un nombre fixe de threads, tandis qu'un pool de threads extensible peut ajouter des threads dynamiquement
    - **b) Un pool de threads fixe a un nombre fixe de threads qui ne changent pas, tandis qu'un pool de threads extensible peut ajouter ou supprimer des threads en fonction de la charge**
    - c) Il n'y a pas de différence, ce sont des termes interchangeables

25. Quelle est la méthode utilisée pour planifier l'exécution périodique d'une tâche dans un pool de threads en Java ?
    - a) scheduleTask()
    - **b) scheduleAtFixedRate()**
    - c) scheduleWithFixedDelay()

26. Quelle est la différence entre scheduleAtFixedRate() et scheduleWithFixedDelay() dans un pool de threads en Java ?
    - **a) scheduleAtFixedRate() exécute la tâche à intervalles réguliers, tandis que scheduleWithFixedDelay() exécute la tâche après un délai fixe après la fin de l'exécution précédente**
    - b) scheduleWithFixedDelay() exécute la tâche à intervalles réguliers, tandis que scheduleAtFixedRate() exécute la tâche après un délai fixe après la fin de l'exécution précédente
    - c) Il n'y a pas de différence, ce sont des termes interchangeables

27. Comment peut-on récupérer le résultat d'une tâche soumise à un pool de threads en Java ?
    - **a) En utilisant la classe Future**
    - b) En utilisant la classe Result
    - c) En utilisant la classe ThreadResult

28. Quelle méthode est utilisée pour obtenir le résultat d'une tâche soumise à un pool de threads en Java ?
    - a) getResult()
    - **b) get()**
    - c) retrieve()

29. Comment peut-on gérer les exceptions lors de l'exécution d'une tâche soumise à un pool de threads en Java ?
    - **a) En utilisant la méthode submit() qui renvoie une Future contenant une exception**
    - b) En utilisant la méthode execute() qui lance automatiquement les exceptions
    - c) En utilisant la méthode handleException() dans le pool de threads

30. Quelle classe est utilisée pour synchroniser l'accès à une ressource partagée en Java ?
    - **a) java.util.concurrent.locks.Lock**
    - b) java.util.concurrent.sync.SyncLock
    - c) java.util.concurrent.ThreadLock

31. Quelle méthode est utilisée pour verrouiller une ressource avec un Lock en Java ?
    - a) lock()
    - **b) lock()**
    - c) synchronize()

32. Comment peut-on éviter les deadlocks dans les threads en Java ?
    - a) En utilisant des verrous synchronisés
    - **b) En utilisant l'ordre de verrouillage cohérent**
    - c) En utilisant des threads indépendants

33. Quelle classe est utilisée pour créer des barrières de synchronisation en Java ?
    - a) java.util.concurrent.sync.SyncBarrier
    - **b) java.util.concurrent.CyclicBarrier**
    - c) java.util.concurrent.SynchronizationBarrier

34. Quelle méthode est utilisée pour attendre que tous les threads atteignent la barrière dans une CyclicBarrier en Java ?
    - a) wait()
    - **b) await()**
    - c) pause()

35. Comment peut-on réinitialiser une barrière de synchronisation en Java ?
    - a) reset()
    - **b) await()**
    - c) restart()

36. Quelle classe est utilisée pour créer des sémaphores en Java ?
    - a) java.util.concurrent.Semaphore
    - **b) java.util.concurrent.Semaphore**
    - c) java.util.concurrent.sync.SyncSemaphore

37. Quelle méthode est utilisée pour acquérir un sémaphore en Java ?
    - **a) acquire()**
    - b) wait()
    - c) take()

38. Comment peut-on libérer un sémaphore en Java ?
    - a) free()
    - **b) release()**
    - c) give()

39. Quelle classe est utilisée pour créer des compteurs cycliques en Java ?
    - **a) java.util.concurrent.CountDownLatch**
    - b) java.util.concurrent.sync.SyncCounter
    - c) java.util.concurrent.CyclicCounter

40. Quelle méthode est utilisée pour attendre que le compteur atteigne zéro dans un CountDownLatch en Java ?
    - a) wait()
    - **b) await()**
    - c) pause()

41. Comment peut-on décrémenter le compteur d'un CountDownLatch en Java ?
    - a) decrement()
    - **b) countDown()**
    - c) decrease()

42. Quelle classe est utilisée pour exécuter des tâches asynchrones en Java ?
    - a) java.util.concurrent.AsyncExecutor
    - **b) java.util.concurrent.ExecutorService**
    - c) java.util.concurrent.TaskExecutor

43. Quelle méthode est utilisée pour soumettre une tâche asynchrone à un ExecutorService en Java ?
    - a) executeTask()
    - **b) submit()**
    - c) addTask()

44. Comment peut-on obtenir le résultat d'une tâche asynchrone soumise à un ExecutorService en Java ?
    - a) getResult()
    - **b) Future.get()**
    - c) retrieveResult()

45. Quelle méthode est utilisée pour exécuter une tâche après un délai donné dans un ScheduledExecutorService en Java ?
    - a) executeAfterDelay()
    - **b) schedule()**
    - c) runAfterDelay()

46. Comment peut-on annuler l'exécution d'une tâche planifiée dans un ScheduledExecutorService en Java ?
    - a) cancelTask()
    - **b) cancel()**
    - c) stopTask()

47. Quelle classe est utilisée pour créer des files d'attente concurrentes en Java ?
    - **a) java.util.concurrent.ConcurrentLinkedQueue**
    - b) java.util.concurrent.SyncQueue
    - c) java.util.concurrent.ConcurrentQueue

48. Quelle méthode est utilisée pour ajouter un élément à une file d'attente concurrente en Java ?
    - a) add()
    - **b) offer()**
    - c) enqueue()

49. Comment peut-on récupérer et supprimer un élément de tête d'une file d'attente concurrente en Java ?
    - a) retrieve()
    - **b) poll()**
    - c) dequeue()

50. Quelle méthode est utilisée pour vérifier si une file d'attente concurrente est vide en Java ?
    - a) isEmpty()
    - **b) isEmpty()**
    - c) isQueueEmpty()
```
<br>

## PROGRAMMATION RÉSEAU AVEC LES SOCKETS EN JAVA :
```markdown

1. Qu'est-ce qu'un socket en programmation réseau en Java ?
   - a) Une bibliothèque de fonctions pour les entrées et sorties
   - **b) Un point de communication permettant l'échange de données entre les applications**
   - c) Une classe Java pour gérer les threads

2. Quelle classe est utilisée pour créer un socket serveur en Java ?
   - a) SocketClient
   - **b) ServerSocket**
   - c) DatagramSocket

3. Quelle méthode est utilisée pour écouter les connexions entrantes sur un socket serveur en Java ?
   - a) connect()
   - **b) accept()**
   - c) listen()

4. Quelle classe est utilisée pour représenter une connexion client dans un socket serveur en Java ?
   - **a) Socket**
   - b) ServerSocket
   - c) DatagramSocket

5. Comment peut-on obtenir le flux d'entrée d'un socket en Java ?
   - a) getInputStream()
   - **b) getInputStream()**
   - c) getInput()

6. Comment peut-on obtenir le flux de sortie d'un socket en Java ?
   - a) getOutputStream()
   - **b) getOutputStream()**
   - c) getOutput()

7. Quelle méthode est utilisée pour envoyer des données sur un socket en Java ?
   - a) send()
   - **b) write()**
   - c) transmit()

8. Quelle méthode est utilisée pour recevoir des données d'un socket en Java ?
   - a) receive()
   - **b) read()**
   - c) accept()

9. Comment peut-on fermer une connexion socket en Java ?
   - **a) En appelant la méthode close()**
   - b) En appelant la méthode disconnect()
   - c) En appelant la méthode shutdown()

10. Quelle classe est utilisée pour créer un socket client en Java ?
    - **a) Socket**
    - b) ServerSocket
    - c) DatagramSocket

11. Quelle méthode est utilisée pour se connecter à un serveur distant avec un socket client en Java ?
    - a) bind()
    - **b) connect()**
    - c) establish()

12. Quelle est la différence entre un socket TCP et un socket UDP en Java ?
    - a) Aucune différence, ce sont des termes interchangeables
    - **b) Un socket TCP fournit un flux de données fiable et orienté connexion, tandis qu'un socket UDP fournit un flux de données non fiable et sans connexion**
    - c) Un socket TCP utilise le protocole HTTP, tandis qu'un socket UDP utilise le protocole FTP

13. Quelle classe est utilisée pour envoyer et recevoir des paquets UDP en Java ?
    - a) Datagram
    - **b) DatagramSocket**
    - c) SocketPacket

14. Comment peut-on envoyer un paquet UDP à un serveur distant en Java ?
    - **a) En utilisant la classe DatagramPacket et la méthode send()**
    - b) En utilisant la classe SocketPacket et la méthode transmit()
    - c) En utilisant la classe DataPacket et la méthode dispatch()

15. Quelle méthode est utilisée pour recevoir un paquet UDP sur un socket en Java ?
    - a) getPacket()
    - **b) receive()**
    - c) fetchPacket()

16. Quelle classe est utilisée pour représenter une adresse IP en Java ?
    - a) IPAddress
    - **b) InetAddress**
    - c) IPAddr

17. Comment peut-on obtenir l'adresse IP d'un hôte à partir de son nom de domaine en Java ?
    - a) getHostIP()
    - **b) getByName()**
    - c) resolveIP()

18. Quelle classe est utilisée pour représenter un port de communication en Java ?
    - a) SocketPort
    - **b) InetSocketAddress**
    - c) PortAddress

19. Quelle méthode est utilisée pour obtenir le port d'un socket en Java ?
    - a) getSocketPort()
    - **b) getPort()**
    - c) fetchPort()

20. Comment peut-on gérer les exceptions liées à la programmation réseau en Java ?
    - **a) En utilisant des blocs try-catch pour capturer et traiter les exceptions**
    - b) En ignorant les exceptions et en continuant l'exécution
    - c) En redémarrant l'application en cas d'exception

21. Quelle classe est utilisée pour représenter un serveur multithread en Java ?
    - a) MultiServerSocket
    - **b) ServerSocket**
    - c) ThreadedServer

22. Quelle méthode est utilisée pour accepter les connexions entrantes dans un serveur multithread en Java ?
    - a) connect()
    - **b) accept()**
    - c) listen()

23. Comment peut-on créer un thread pour gérer une connexion client dans un serveur multithread en Java ?
    - a) En créant une nouvelle instance de la classe Thread
    - **b) En étendant la classe Thread**
    - c) En utilisant la classe ThreadPool

24. Quelle méthode est utilisée pour démarrer l'exécution d'un thread en Java ?
    - a) start()
    - **b) run()**
    - c) execute()

25. Quelle méthode est utilisée pour arrêter l'exécution d'un thread en Java ?
    - a) stop()
    - **b) interrupt()**
    - c) end()

26. Quelle classe est utilisée pour créer des flux de données de plus haut niveau en Java ?
    - a) StreamSocket
    - **b) BufferedReader/BufferedWriter**
    - c) DataSocket

27. Quelle méthode est utilisée pour lire une ligne de texte à partir d'un flux de données en Java ?
    - a) read()
    - **b) readLine()**
    - c) fetchLine()

28. Quelle méthode est utilisée pour écrire une ligne de texte dans un flux de données en Java ?
    - a) write()
    - **b) writeLine()**
    - c) transmitLine()

29. Quelle classe est utilisée pour sérialiser un objet en Java ?
    - a) ObjectSerializer
    - **b) ObjectOutputStream**
    - c) ObjectStream

30. Quelle méthode est utilisée pour écrire un objet sérialisé dans un flux de données en Java ?
    - a) writeObject()
    - **b) write()**
    - c) serialize()

31. Quelle classe est utilisée pour désérialiser un objet en Java ?
    - a) ObjectDeserializer
    - **b) ObjectInputStream**
    - c) ObjectStream

32. Quelle méthode est utilisée pour lire

 un objet désérialisé à partir d'un flux de données en Java ?
    - a) readObject()
    - **b) read()**
    - c) deserialize()

33. Quelle classe est utilisée pour représenter une URL en Java ?
    - a) URILink
    - **b) URL**
    - c) URILocation

34. Quelle méthode est utilisée pour ouvrir une connexion HTTP à partir d'une URL en Java ?
    - **a) openConnection()**
    - b) connect()
    - c) establishConnection()

35. Quelle classe est utilisée pour envoyer des requêtes HTTP en Java ?
    - **a) HttpURLConnection**
    - b) HttpRequest
    - c) HttpSocket

36. Quelle méthode est utilisée pour définir la méthode de requête (GET, POST, etc.) dans une connexion HTTP en Java ?
    - a) setRequestMethod()
    - **b) setRequestMethod()**
    - c) setRequestType()

37. Comment peut-on ajouter des paramètres à une requête HTTP en Java ?
    - a) En ajoutant les paramètres à l'URL de la requête
    - **b) En utilisant la méthode setDoOutput(true) et en écrivant les paramètres dans le flux de sortie**
    - c) En utilisant la méthode setParameters() de la classe HttpURLConnection

38. Quelle méthode est utilisée pour obtenir le code de statut d'une réponse HTTP en Java ?
    - a) getResponseCode()
    - **b) getStatusCode()**
    - c) fetchResponseCode()

39. Quelle méthode est utilisée pour obtenir les en-têtes d'une réponse HTTP en Java ?
    - **a) getHeaderFields()**
    - b) getResponseHeaders()
    - c) fetchHeaders()

40. Quelle classe est utilisée pour lire les données de réponse d'une requête HTTP en Java ?
    - a) HttpResponseReader
    - **b) BufferedReader**
    - c) HttpDataReader

41. Quelle méthode est utilisée pour lire une ligne de texte de la réponse HTTP en Java ?
    - a) readLine()
    - **b) readLine()**
    - c) fetchLine()

42. Quelle méthode est utilisée pour fermer une connexion HTTP en Java ?
    - a) close()
    - **b) disconnect()**
    - c) endConnection()

43. Quelle classe est utilisée pour représenter un serveur HTTP en Java ?
    - a) HttpServerSocket
    - **b) HttpServer**
    - c) HttpSocketServer

44. Quelle méthode est utilisée pour démarrer un serveur HTTP en Java ?
    - **a) start()**
    - b) run()
    - c) begin()

45. Comment peut-on spécifier le port sur lequel le serveur HTTP écoute en Java ?
    - a) En utilisant la méthode setPort() de la classe HttpServer
    - **b) En utilisant le constructeur de la classe HttpServer avec le numéro de port en argument**
    - c) En utilisant la méthode bind() de la classe HttpServer

46. Quelle classe est utilisée pour représenter une requête HTTP reçue par un serveur en Java ?
    - a) HttpRequestSocket
    - **b) HttpExchange**
    - c) HttpMessage

47. Quelle méthode est utilisée pour obtenir la méthode de requête (GET, POST, etc.) d'une requête HTTP en Java ?
    - a) getMethod()
    - **b)

 getRequestMethod()**
    - c) fetchRequestMethod()

48. Quelle méthode est utilisée pour obtenir le chemin de la ressource demandée dans une requête HTTP en Java ?
    - **a) getRequestURI()**
    - b) getResourcePath()
    - c) fetchRequestPath()

49. Quelle méthode est utilisée pour obtenir les paramètres de requête d'une requête HTTP en Java ?
    - a) getQueryParameters()
    - **b) getParameterMap()**
    - c) fetchParameters()

50. Quelle méthode est utilisée pour envoyer une réponse HTTP à une requête en Java ?
    - a) sendResponse()
    - **b) sendResponseHeaders()**
    - c) transmitResponse()
```
<br>

## GÉNÉRICITÉ EN JAVA :
```markdown

1. Qu'est-ce que la généricité en Java ?
   - a) Une fonction permettant de générer des nombres aléatoires
   - **b) Une fonctionnalité permettant de créer des classes et des méthodes paramétrées**
   - c) Une fonctionnalité permettant d'écrire des algorithmes récursifs

2. Quel est l'avantage principal de l'utilisation de la généricité en Java ?
   - a) Une réduction de la taille du code source
   - **b) Une amélioration de la sécurité et de la robustesse du code**
   - c) Une augmentation de la vitesse d'exécution du programme

3. Comment déclare-t-on une classe générique en Java ?
   - a) En utilisant le mot-clé "generic" avant le mot-clé "class"
   - **b) En utilisant des chevrons ("< >") après le nom de la classe**
   - c) En utilisant le mot-clé "generic" après le nom de la classe

4. Comment déclare-t-on une méthode générique en Java ?
   - a) En utilisant le mot-clé "generic" avant le mot-clé "method"
   - **b) En utilisant des chevrons ("< >") avant le type de retour de la méthode**
   - c) En utilisant le mot-clé "generic" après le nom de la méthode

5. Quel est le symbole utilisé pour représenter un type générique inconnu en Java ?
   - a) "T"
   - **b) "E"**
   - c) "G"

6. Comment spécifie-t-on le type d'un paramètre générique lors de l'appel d'une méthode en Java ?
   - a) En utilisant le mot-clé "generic" avant le nom du paramètre
   - **b) En spécifiant le type entre chevrons ("< >") après le nom de la méthode**
   - c) En utilisant le mot-clé "generic" après le nom du paramètre

7. Quel est l'avantage de l'utilisation de wildcards ("?" wildcard) en Java ?
   - **a) Permet de représenter n'importe quel type générique**
   - b) Permet de restreindre le type générique à un seul type spécifique
   - c) Permet de générer des types de données aléatoires

8. Quelle est la différence entre une généricité non bornée et une généricité bornée en Java ?
   - a) Aucune différence, ce sont des termes interchangeables
   - **b) La généricité non bornée permet d'utiliser n'importe quel type générique, tandis que la généricité bornée impose des contraintes sur le type générique**
   - c) La généricité non bornée est plus performante que la généricité bornée

9. Comment spécifie-t-on une contrainte de type (type constraint) dans une généricité bornée en Java ?
   - **a) En utilisant le mot-clé "extends" suivi du type de contrainte**
   - b) En utilisant le mot-clé "constraint" suivi du type de contrainte
   - c) En utilisant le mot-clé "bound" suivi du type de contrainte

10. Quel est le résultat de l'opération de type "casting" d'un objet générique en Java ?
    - a) L'objet générique est converti en un autre type d'objet spécifique
    - **b) L'objet générique est converti en un type non spécifié (raw type)**
    - c) L'opération de type "casting" n'est pas autorisée sur les objets génériques

11. Qu'est-ce qu'une classe générique paramétrée en Java ?
    - a) Une classe dont les méthodes prennent des paramètres génériques
    - **b) Une classe dont le type est déterminé au moment de l'instanciation**
    - c) Une classe qui ne peut être instanciée que dans des contextes spécifiques

12. Comment déclare-t-on une variable d'un type générique en Java ?
    - a) En utilisant le mot-clé "generic" avant le nom de la variable
    - **b) En spécifiant le type entre chevrons ("< >") après le nom de la variable**
    - c) En utilisant le mot-clé "generic" après le nom de la variable

13. Qu'est-ce qu'une méthode générique paramétrée en Java ?
    - a) Une méthode qui peut prendre un nombre variable de paramètres
    - **b) Une méthode dont le type de retour et/ou les types des paramètres sont génériques**
    - c) Une méthode qui peut être appelée avec différents types de valeurs de retour

14. Comment utilise-t-on une classe générique paramétrée lors de l'instanciation en Java ?
    - **a) En spécifiant le type générique entre chevrons ("< >") après le nom de la classe**
    - b) En utilisant le mot-clé "generic" avant le nom de la classe
    - c) En utilisant le mot-clé "generic" après le nom de la classe

15. Quelle est la relation entre une classe générique et sa classe de base en Java ?
    - **a) Une classe générique est une extension de sa classe de base**
    - b) Une classe générique est une version spécialisée de sa classe de base
    - c) Une classe générique et sa classe de base sont indépendantes l'une de l'autre

16. Comment utilise-t-on une méthode générique paramétrée en Java ?
    - a) En spécifiant le type générique entre chevrons ("< >") avant le nom de la méthode
    - **b) En spécifiant le type générique entre chevrons ("< >") avant le type de retour de la méthode**
    - c) En utilisant le mot-clé "generic" après le nom de la méthode

17. Qu'est-ce qu'une liste générique en Java ?
    - a) Une liste qui peut contenir des éléments de différents types
    - **b) Une liste dont le type des éléments est spécifié lors de la création de la liste**
    - c) Une liste qui ne peut contenir que des objets de type String

18. Comment déclare-t-on une liste générique en Java ?
    - a) En utilisant le mot-clé "generic" avant le nom de la liste
    - **b) En spécifiant le type générique entre chevrons ("< >") après le nom de la liste**
    - c) En utilisant le mot-clé "generic" après le nom de la liste

19. Comment ajoute-t-on un élément à une liste générique en Java ?
    - **a) En utilisant la méthode "add()" de la liste**
    - b) En utilisant la méthode "insert()" de la liste
    - c) En utilisant la méthode "append()" de la liste

20. Comment récupère-t-on un élément d'une liste générique en Java ?
    - **a) En utilisant la méthode "get()" de la liste**
    - b) En utilisant la méthode "retrieve()" de la liste
    - c) En utilisant la méthode "fetch()" de la liste

21. Comment déclare-t-on une méthode générique paramétrée avec une contrainte de type en Java ?
    - a) En utilisant le mot-clé "generic" avant le mot-clé "method" et en spécifiant la contrainte de type entre chevrons ("< >")
    - **b) En utilisant le mot-clé "generic" avant le type de retour de la méthode et en spécifiant la contrainte de type après le nom du paramètre**
    - c) En utilisant le mot-clé "generic" après le nom de la méthode et en spécifiant la contrainte de type avant le type de retour de la méthode

22. Qu'est-ce qu'une classe générique sans spécification de type en Java ?
    - **a) Une classe générique qui peut être utilisée avec n'importe quel type**
    - b) Une classe générique qui ne peut être utilisée qu'avec des types spécifiques
    - c) Une classe générique qui nécessite une spécification de type lors de l'utilisation

23. Comment utilise-t-on une classe générique sans spécification de type en Java ?
    - a) En spécifiant le type générique entre chevrons ("< >") après le nom de la classe
    - **b) En utilisant la classe sans spécifier de type générique**
    - c) En utilisant le mot-clé "generic" après le nom de la classe

24. Quelle est la différence entre une classe générique et une classe non générique en Java ?
    - a) Une classe générique peut être utilisée avec des types différents, tandis qu'une classe non générique est spécifique à un seul type
    - **b) Une classe générique permet de créer des instances spécifiques à un type déterminé, tandis qu'une classe non générique ne nécessite pas de spécification de type**
    - c) Une classe générique est plus performante qu'une classe non générique

25. Comment spécifie-t-on plusieurs contraintes de type dans une généricité bornée en Java ?
    - a) En utilisant des parenthèses pour séparer les contraintes de type
    - **b) En utilisant le mot-clé "extends" suivi de plusieurs types de contrainte séparés par des virgules**
    - c) En utilisant le mot-clé "constraint" suivi de plusieurs types de contrainte séparés par des virgules

26. Qu'est-ce qu'une méthode générique paramétrée avec une contrainte de type multiple en Java ?
    - **a) Une méthode générique qui accepte plusieurs types génériques en respectant les contraintes spécifiées**
    - b) Une méthode générique qui accepte plusieurs paramètres de type générique
    - c) Une méthode générique qui impose plusieurs contraintes de type sur un seul paramètre

27. Comment déclare-t-on une classe générique avec plusieurs paramètres de type en Java ?
    - a) En utilisant le mot-clé "generic" avant chaque paramètre de type
    - **b) En spécifiant les paramètres de type entre chevrons ("< >") séparés par des virgules après le nom de la classe**
    - c) En utilisant le mot-clé "generic" après chaque paramètre de type

28. Quelle est la différence entre une classe générique et une classe paramétrée en Java ?
    - a) Aucune différence, ce sont des termes interchangeables
    - **b) Une classe générique est une classe dont le type est déterminé à l'instanciation, tandis qu'une classe paramétrée est une classe dont le type est spécifié lors de l'utilisation**
    - c) Une classe générique ne peut pas avoir de paramètres, tandis qu'une classe paramétrée peut en avoir

29. Comment déclare-t-on une méthode générique avec plusieurs paramètres de type en Java ?
    - a) En utilisant le mot-clé "generic" avant chaque paramètre de type
    - **b) En spécifiant les paramètres de type entre chevrons ("< >") séparés par des virgules avant le type de retour de la méthode**
    - c) En utilisant le mot-clé "generic" après chaque paramètre de type

30. Comment déclare-t-on une liste générique avec plusieurs paramètres de type en Java ?
    - a) En utilisant le mot-clé "generic" avant chaque paramètre de type
    - **b) En spécifiant les paramètres de type entre chevrons ("< >") séparés par des virgules après le nom de la liste**
    - c) En utilisant le mot-clé "generic" après chaque paramètre de type

31. Qu'est-ce qu'une interface générique en Java ?
    - **a) Une interface dont le type est déterminé lors de l'implémentation**
    - b) Une interface qui ne peut être implémentée que par des classes génériques
    - c) Une interface qui ne peut être utilisée qu'avec des types spécifiques

32. Comment déclare-t-on une interface générique en Java ?
    - a) En utilisant le mot-clé "generic" avant le mot-clé "interface"
    - **b) En spécifiant le type générique entre chevrons ("< >") après le nom de l'interface**
    - c) En utilisant le mot-clé "generic" après le nom de l'interface

33. Quelle est la différence entre une classe générique et une interface générique en Java ?
    - **a) Une classe générique est une classe paramétrée qui peut être instanciée, tandis qu'une interface générique est une interface paramétrée qui doit être implémentée**
    - b) Une classe générique est utilisée pour définir des types de données, tandis qu'une interface générique est utilisée pour définir des comportements
    - c) Il n'y a pas de différence, les termes sont interchangeables

34. Qu'est-ce qu'une méthode générique dans une interface générique en Java ?
    - a) Une méthode qui peut prendre un nombre variable de paramètres génériques
    - **b) Une méthode dont le type de retour et/ou les types des paramètres sont génériques**
    - c) Une méthode qui peut être appelée avec différents types de valeurs de retour

35. Comment implémente-t-on une interface générique en Java ?
    - **a) En spécifiant le type générique entre chevrons ("< >") lors de l'implémentation de l'interface**
    - b) En utilisant le mot-clé "generic" avant le nom de l'interface lors de l'implémentation
    - c) En utilisant le mot-clé "generic" après le nom de l'interface lors de l'implémentation

36. Qu'est-ce qu'une classe générique avec une clause "super" en Java ?
    - a) Une classe générique qui peut être utilisée avec n'importe quel type
    - b) Une classe générique qui impose des contraintes sur le type générique en utilisant le mot-clé "super"
    - **c) Une classe générique qui accepte des types plus génériques que le type spécifié**

37. Comment utilise-t-on une classe générique avec une clause "super" en Java ?
    - a) En spécifiant le type générique entre chevrons ("< >") après le nom de la classe
    - **b) En spécifiant le type générique suivi du mot-clé "super" et du type spécifique entre chevrons ("< >") après le nom de la classe**
    - c) En utilisant le mot-clé "generic" après le nom de la classe

38. Qu'est-ce qu'une méthode générique avec une clause "super" en Java ?
    - **a) Une méthode générique qui accepte des paramètres d'un type générique ou de tout type qui est un supertype du type générique**
    - b) Une méthode générique qui impose des contraintes sur les types de paramètres en utilisant le mot-clé "super"
    - c) Une méthode générique qui impose des contraintes sur le type de retour en utilisant le mot-clé "super"

39. Comment utilise-t-on une méthode générique avec une clause "super" en Java ?
    - **a) En spécifiant le type générique suivi du mot-clé "super" et du type spécifique entre chevrons ("< >") avant le type de retour de la méthode**
    - b) En spécifiant le type générique suivi du mot-clé "super" et du type spécifique entre chevrons ("< >") après le nom de la méthode
    - c) En utilisant le mot-clé "generic" après le nom de la méthode

40. Qu'est-ce qu'une méthode générique avec une clause "extends" en Java ?
    - **a) Une méthode générique qui accepte des paramètres d'un type générique ou de tout type qui est un subtype du type générique**
    - b) Une méthode générique qui impose des contraintes sur les types de paramètres en utilisant le mot-clé "extends"
    - c) Une méthode générique qui impose des contraintes sur le type de retour en utilisant le mot-clé "extends"

41. Comment utilise-t-on une méthode générique avec une clause "extends" en Java ?
    - a) En spécifiant le type générique suivi du mot-clé "extends" et du type spécifique entre chevrons ("< >") avant le type de retour de la méthode
    - **b) En spécifiant le type générique suivi du mot-clé "extends" et du type spécifique entre chevrons ("< >") après le nom de la méthode**
    - c) En utilisant le mot-clé "generic" après le nom de la méthode

42. Qu'est-ce qu'une classe générique avec des wildcard en Java ?
    - a) Une classe générique qui peut être utilisée avec des types spécifiques et des types génériques
    - **b) Une classe générique qui accepte des types inconnus ou non spécifiés en utilisant le symbole "?"**
    - c) Une classe générique qui impose des contraintes sur les types de paramètres en utilisant le mot-clé "wildcard"

43. Comment utilise-t-on une classe générique avec des wildcard en Java ?
    - **a) En utilisant le symbole "?" à la place d'un type spécifique lors de l'instanciation de la classe**
    - b) En utilisant le mot-clé "generic" après le nom de la classe
    - c) En spécifiant le type générique entre chevrons ("< >") après le nom de la classe

44. Qu'est-ce qu'une méthode générique avec des wildcard en Java ?
    - **a) Une méthode générique qui accepte des paramètres d'un type spécifique ou de tout type inconnu en utilisant le symbole "?"**
    - b) Une méthode générique qui impose des contraintes sur les types de paramètres en utilisant le mot-clé "wildcard"
    - c) Une méthode générique qui impose des contraintes sur le type de retour en utilisant le mot-clé "wildcard"

45. Comment utilise-t-on une méthode générique avec des wildcard en Java ?
    - **a) En utilisant le symbole "?" à la place d'un type spécifique lors de l'appel de la méthode**
    - b) En utilisant le mot-clé "generic" après le nom de la méthode
    - c) En spécifiant le type générique entre chevrons ("< >") avant le type de retour de la méthode

46. Quelle est la différence entre "?" et "? extends Type" dans les wildcard en Java ?
    - **a) "?" accepte n'importe quel type, tandis que "? extends Type" accepte un type spécifique ou tout sous-type de ce type**
    - b) "?" accepte un type spécifique ou tout sous-type de ce type, tandis que "? extends Type" accepte n'importe quel type
    - c) Il n'y a pas de différence, les deux expressions sont équivalentes

47. Comment utilise-t-on un wildcard avec une clause "super" dans une méthode générique en Java ?
    - a) En utilisant le symbole "?" suivi du mot-clé "super" et du type spécifique entre chevrons ("< >") avant le type de retour de la méthode
    - **b) En utilisant le symbole "?" suivi du mot-clé "super" et du type spécifique entre chevrons ("< >") après le nom du paramètre de la méthode**
    - c) En utilisant le mot-clé "generic" après le nom de la méthode

48. Comment utilise-t-on un wildcard avec une clause "extends" dans une méthode générique en Java ?
    - a) En utilisant le symbole "?" suivi du mot-clé "extends" et du type spécifique entre chevrons ("< >") avant le type de retour de la méthode
    - **b) En utilisant le symbole "?" suivi du mot-clé "extends" et du type spécifique entre chevrons ("< >") après le nom du paramètre de la méthode**
    - c) En utilisant le mot-clé "generic" après le nom de la méthode

49. Qu'est-ce qu'une méthode générique avec des wildcard dans une interface générique en Java ?
    - a) Une méthode générique qui accepte des paramètres d'un type générique ou de tout type inconnu en utilisant le symbole "?"
    - **b) Une méthode générique qui accepte des paramètres d'un type spécifique ou de tout sous-type de ce type en utilisant le symbole "? extends Type"**
    - c) Une méthode générique qui impose des contraintes sur les types de paramètres en utilisant le mot-clé "wildcard"

50. Comment utilise-t-on une méthode générique avec des wildcard dans une interface générique en Java ?
    - a) En utilisant le symbole "?" à la place d'un type spécifique lors de l'appel de la méthode
    - **b) En utilisant le symbole "? extends Type" à la place d'un type spécifique lors de l'appel de la méthode**
    - c) En spécifiant le type générique entre chevrons ("< >") après le nom de l'interface
```


# Exercice de compilation :

```markdown
**Exercice 1 :**
```java
public class GenericsExercise1 {

    public static void main(String[] args) {
        Box<Integer> intBox = new Box<>();
        intBox.set(10);
        
        System.out.println(intBox.get());
    }
}

class Box<T> {
    private T value;

    public void set(T value) {
        this.value = value;
    }

    public T get() {
        return value;
    }
}
```
**Solution :** Le code compile sans erreur. L'exercice déclare une classe générique `Box` qui contient une variable de type `T`. La méthode `set` assigne une valeur à la variable `value` et la méthode `get` retourne cette valeur.

**Exercice 2 :**
```java
public class GenericsExercise2 {

    public static void main(String[] args) {
        Box<String> strBox = new Box<>();
        strBox.set("Hello");
        
        System.out.println(strBox.get());
    }
}

class Box<T> {
    private T value;

    public void set(T value) {
        this.value = value;
    }

    public T get() {
        return value;
    }
}
```
**Solution :** Le code compile sans erreur. Ici, la classe générique `Box` est instanciée avec le type `String`. La méthode `set` assigne une chaîne de caractères à la variable `value` et la méthode `get` retourne cette chaîne.


**Exercice 3 :**
```java
public class GenericsExercise3 {

    public static void main(String[] args) {
        Box<Integer> intBox = new Box<>();
        intBox.set("Hello");
        
        System.out.println(intBox.get());
    }
}

class Box<T> {
    private T value;

    public void set(T value) {
        this.value = value;
    }

    public T get() {
        return value;
    }
}
```
**Solution :** Le code ne compile pas en raison d'une incompatibilité de types. La classe `Box` est déclarée avec le type générique `T` et la variable `value` est également de type `T`. Dans cet exercice, nous essayons de définir une valeur de type `String` dans une `Box<Integer>`, ce qui entraîne une erreur de compilation.

**Exercice 4 :**
```java
public class GenericsExercise4 {

    public static void main(String[] args) {
        Box<Integer> intBox = new Box<>();
        intBox.set(10);
        
        System.out.println(intBox.get().toUpperCase());
    }
}

class Box<T> {
    private T value;

    public void set(T value) {
        this.value = value;
    }

    public T get() {
        return value;
    }
}
```
**Solution :** Le code ne compile pas car la méthode `toUpperCase()` n'est pas définie pour le type `T`. La classe `Box` est déclarée avec le type générique `T`, mais la méthode `toUpperCase()` appartient à la classe `String`. Par conséquent, l'appel de `toUpperCase()` sur la valeur de la `Box` entraîne une erreur de compilation.



**Exercice 5 :**
```java
public class GenericsExercise5 {

    public static void main(String[] args) {
        Box<String> strBox = new Box<>();
        strBox.set(10);
        
        System.out.println(strBox.get());
    }
}

class Box<T> {
    private T value;

    public void set(T value) {
        this.value = value;
    }

    public T get() {
        return value;
    }
}
```
**Solution :** Le code ne compile pas en raison d'une incompatibilité de types. La classe `Box` est déclarée avec le type générique `T` et la variable `value` est également de type `T`. Dans cet exercice, nous essayons de définir une valeur de type `Integer` dans une `Box<String>`, ce qui entraîne une erreur de compilation.

**Exercice 6 :**
```java
public class GenericsExercise6 {

    public static void main(String[] args) {
        Box<Object> objBox = new Box<>();
        objBox.set("Hello");
        
        String value = objBox.get();
        System.out.println(value.length());
    }
}

class Box<T> {
    private T value;

    public void set(T value) {
        this.value = value;
    }

    public T get() {
        return value;
    }
}
```
**Solution :** Le code compile sans erreur. La classe `Box` est instanciée avec le type générique `Object`, qui est la superclasse de tous les types en Java. Ainsi, nous pouvons stocker une chaîne de caractères dans la `Box<Object>`. La méthode `get` retourne la valeur en tant qu'objet, et nous pouvons ensuite assigner cette valeur à une variable de type `String` et appeler des méthodes sur celle-ci.



**Exercice 7 :**
```java
public class GenericsExercise7 {

    public static void main(String[] args) {
        Box<?> box = new Box<>("Hello");
        
        System.out.println(box.get());
    }
}

class Box<T> {
    private T value;

    public Box(T value) {
        this.value = value;
    }

    public T get() {
        return value;
    }
}
```
**Solution :** Le code compile sans erreur. La classe `Box` est instanciée avec le type générique `T`. Dans cet exercice, nous utilisons un caractère générique `?` pour la variable `box`, ce qui signifie que nous ne connaissons pas exactement le type de `box`. Cela permet de stocker une valeur de n'importe quel type dans `box` et de la récupérer avec la méthode `get()`.

**Exercice 8 :**
```java
public class GenericsExercise8 {

    public static void main(String[] args) {
        Box<String> box = new Box<>();
        box.set("Hello");
        
        System.out.println(box.get().length());
    }
}

class Box<T> {
    private T value;

    public void set(T value) {
        this.value = value;
    }

    public T get() {
        return value;
    }
}
```
**Solution :** Le code compile sans erreur. La classe `Box` est instanciée avec le type générique `String`. La méthode `set` assigne une chaîne de caractères à la variable `value` et la méthode `get` retourne cette chaîne. Dans cet exercice, nous appelons la méthode `length()` sur la valeur de la `Box`, qui est une chaîne de caractères.


**Exercice 9 :**
```java
public class GenericsExercise9 {

    public static void main(String[] args) {
        Box<Number> numberBox = new Box<>();
        numberBox.set(10);
        
        System.out.println(numberBox.get().doubleValue());
    }
}

class Box<T extends Number> {
    private T value;

    public void set(T value) {
        this.value = value;
    }

    public T get() {
        return value;
    }
}
```
**Solution :** Le code compile sans erreur. La classe `Box` est instanciée avec le type générique `T` qui est restreint à être une sous-classe de `Number`. Dans cet exercice, nous utilisons la méthode `doubleValue()` pour convertir la valeur de la `Box` en un double.

**Exercice 10 :**
```java
public class GenericsExercise10 {

    public static void main(String[] args) {
        Box<String> box = new Box<>();
        box.set("Hello");
        
        System.out.println(box.get().toLowerCase());
    }
}

class Box<T extends CharSequence> {
    private T value;

    public void set(T value) {
        this.value = value;
    }

    public T get() {
        return value;
    }
}
```
**Solution :** Le code compile sans erreur. La classe `Box` est instanciée avec le type générique `T` qui est restreint à être une sous-interface de `CharSequence`, comme `String`. Dans cet exercice, nous appelons la méthode `toLowerCase()` sur la valeur de la `Box`, qui est une chaîne de caractères.


**Exercice 11 :**
```java
public class GenericsExercise1<T extends Number> {
    private T value;

    public GenericsExercise1(T value) {
        this.value = value;
    }

    public double square() {
        return value.doubleValue() * value.doubleValue();
    }

    public static void main(String[] args) {
        GenericsExercise1<Integer> intObj = new GenericsExercise1<>(5);
        System.out.println(intObj.square());

        GenericsExercise1<Double> doubleObj = new GenericsExercise1<>(2.5);
        System.out.println(doubleObj.square());
    }
}
```
**Solution :** La classe `GenericsExercise1` est générique avec une contrainte de type `T extends Number`. Elle possède un constructeur qui accepte une valeur de type `T` et une méthode `square()` qui renvoie le carré de la valeur. Dans le `main()`, nous instancions la classe avec des types `Integer` et `Double` et appelons la méthode `square()` pour obtenir les carrés des valeurs.

**Exercice 12 :**
```java
public class GenericsExercise2<T> {
    private T[] array;

    public GenericsExercise2(T[] array) {
        this.array = array;
    }

    public void printArray() {
        for (T element : array) {
            System.out.println(element);
        }
    }

    public static void main(String[] args) {
        Integer[] intArray = {1, 2, 3, 4, 5};
        GenericsExercise2<Integer> intObj = new GenericsExercise2<>(intArray);
        intObj.printArray();

        String[] strArray = {"Hello", "World"};
        GenericsExercise2<String> strObj = new GenericsExercise2<>(strArray);
        strObj.printArray();
    }
}
```
**Solution :** La classe `GenericsExercise2` est générique avec un type `T`. Elle possède un tableau `array` de type `T` et une méthode `printArray()` qui affiche tous les éléments du tableau. Dans le `main()`, nous instancions la classe avec des tableaux de types `Integer` et `String` et appelons la méthode `printArray()` pour afficher les éléments du tableau.

**Exercice 13 :**
```java
import java.util.ArrayList;
import java.util.List;

public class GenericsExercise3 {

    public static <T extends Comparable<T>> T max(List<T> list) {
        if (list == null || list.isEmpty()) {
            return null;
        }

        T max = list.get(0);
        for (T element : list) {
            if (element.compareTo(max) > 0) {
                max = element;
            }
        }

        return max;
    }

    public static void main(String[] args) {
        List<Integer> intList = new ArrayList<>();
        intList.add(5);
        intList.add(10);
        intList.add(3);
        System.out.println("Max Integer: " + max(intList));

        List<String> strList = new ArrayList<>();
        strList.add("Apple");
        strList.add("Banana");
        strList.add("Carrot");
        System.out.println("Max String: " + max(strList));
    }
}
```
**Solution :** La classe `GenericsExercise3` possède une méthode générique `max()` qui prend une liste de type

 `T` et renvoie l'élément maximum de la liste en utilisant la méthode `compareTo()` de l'interface `Comparable`. Dans le `main()`, nous appelons la méthode `max()` avec des listes d'entiers et de chaînes de caractères pour obtenir l'élément maximum de chaque liste.

**Exercice 14 :**
```java
public class GenericsExercise4 {

    public static <T> void printArray(T[] array) {
        for (T element : array) {
            System.out.println(element);
        }
    }

    public static void main(String[] args) {
        Integer[] intArray = {1, 2, 3, 4, 5};
        printArray(intArray);

        String[] strArray = {"Hello", "World"};
        printArray(strArray);
    }
}
```
**Solution :** La classe `GenericsExercise4` possède une méthode générique `printArray()` qui prend un tableau de type `T` et affiche tous les éléments du tableau. Dans le `main()`, nous appelons la méthode `printArray()` avec des tableaux d'entiers et de chaînes de caractères pour les afficher.

**Exercice 15 :**
```java
public class GenericsExercise5<T> {

    private T value;

    public void setValue(T value) {
        this.value = value;
    }

    public T getValue() {
        return value;
    }

    public static void main(String[] args) {
        GenericsExercise5<? extends Number> numberObj = new GenericsExercise5<>();
        numberObj.setValue(10);
        System.out.println(numberObj.getValue());

        GenericsExercise5<? extends String> stringObj = new GenericsExercise5<>();
        stringObj.setValue("Hello");
        System.out.println(stringObj.getValue());
    }
}
```
**Solution :** La classe `GenericsExercise5` possède une variable `value` de type générique `T` avec des accesseurs. Dans le `main()`, nous créons des instances de `GenericsExercise5` avec des types inconnus (`? extends Number` et `? extends String`). Nous utilisons ensuite les méthodes `setValue()` et `getValue()` pour définir et récupérer les valeurs. Le compilateur autorise ces opérations, mais le type exact de l'objet est inconnu.

**Exercice 16 :**
```java
public class GenericsExercise6 {

    public static <T extends Comparable<T>> T max(T[] array) {
        if (array == null || array.length == 0) {
            return null;
        }

        T max = array[0];
        for (int i = 1; i < array.length; i++) {
            if (array[i].compareTo(max) > 0) {
                max = array[i];
            }
        }

        return max;
    }

    public static void main(String[] args) {
        Integer[] intArray = {5, 10, 3, 8, 1};
        System.out.println("Max Integer: " + max(intArray));

        Double[] doubleArray = {2.5, 4.2, 1.8, 3.7};
        System.out.println("Max Double: " + max(doubleArray));
    }
}
```
**Solution :** La classe `GenericsExercise6` possède une méthode générique `max()` qui prend un tableau de type `T` et renvoie l'élément maximum en utilisant la méthode `compareTo()` de l'interface `Comparable`. Dans le `main()`,

 nous appelons la méthode `max()` avec des tableaux d'entiers et de nombres à virgule flottante pour obtenir l'élément maximum de chaque tableau.

**Exercice 17 :**
```java
public class GenericsExercise7<T> {

    private T value;

    public GenericsExercise7(T value) {
        this.value = value;
    }

    public <U> void print(U obj) {
        System.out.println(obj);
    }

    public static void main(String[] args) {
        GenericsExercise7<String> stringObj = new GenericsExercise7<>("Hello");
        stringObj.print("World");

        GenericsExercise7<Integer> intObj = new GenericsExercise7<>(10);
        intObj.print(20);
    }
}
```
**Solution :** La classe `GenericsExercise7` possède une variable `value` de type générique `T` et un constructeur qui accepte une valeur de type `T`. Elle possède également une méthode générique `print()` qui prend un argument de type `U` et l'affiche. Dans le `main()`, nous instancions la classe avec des types `String` et `Integer` et appelons la méthode `print()` avec des valeurs correspondantes.

**Exercice 18 :**
```java
import java.util.ArrayList;
import java.util.List;

public class GenericsExercise8 {

    public static <T> void copy(List<? super T> dest, List<? extends T> src) {
        for (T element : src) {
            dest.add(element);
        }
    }

    public static void main(String[] args) {
        List<Integer> intList = new ArrayList<>();
        intList.add(1);
        intList.add(2);
        intList.add(3);

        List<Number> numberList = new ArrayList<>();
        copy(numberList, intList);
        System.out.println(numberList);
    }
}
```
**Solution :** La classe `GenericsExercise8` possède une méthode générique `copy()` qui prend une liste de destination de type `<? super T>` et une liste source de type `<? extends T>`. Elle copie les éléments de la liste source dans la liste de destination. Dans le `main()`, nous utilisons la méthode `copy()` pour copier les éléments d'une liste d'entiers dans une liste de nombres.

**Exercice 19 :**
```java
public class GenericsExercise9<T> {

    private T value;

    public GenericsExercise9(T value) {
        this.value = value;
    }

    public <U> U getValue() {
        return (U) value;
    }

    public static void main(String[] args) {
        GenericsExercise9<String> stringObj = new GenericsExercise9<>("Hello");
        String stringValue = stringObj.getValue();
        System.out.println(stringValue);

        GenericsExercise9<Integer> intObj = new GenericsExercise9<>(10);
        Integer intValue = intObj.getValue();
        System.out.println(intValue);
    }
}
```
**Solution :** La classe `GenericsExercise9` possède une variable `value` de type générique `T` et un constructeur qui accepte une valeur de type `T`. Elle possède également une méthode générique `getValue()` qui renvoie la valeur convertie en type `U`. Dans le `main()`, nous instancions la classe avec des types `String` et `Integer` et appelons la méthode `getValue()` pour obtenir les valeurs correspondantes.

**Exercice 20 :**
```java
import java.util.ArrayList;
import java

.util.List;

public class GenericsExercise10 {

    public static <T> List<T> filter(List<T> list, Predicate<? super T> predicate) {
        List<T> result = new ArrayList<>();
        for (T element : list) {
            if (predicate.test(element)) {
                result.add(element);
            }
        }
        return result;
    }

    public static void main(String[] args) {
        List<Integer> intList = new ArrayList<>();
        intList.add(1);
        intList.add(2);
        intList.add(3);
        intList.add(4);
        intList.add(5);

        Predicate<Integer> evenPredicate = num -> num % 2 == 0;
        List<Integer> evenNumbers = filter(intList, evenPredicate);
        System.out.println(evenNumbers);
    }
}
```
**Solution :** La classe `GenericsExercise10` possède une méthode générique `filter()` qui prend une liste de type `T` et un prédicat de type `Predicate<? super T>`. Elle renvoie une nouvelle liste contenant uniquement les éléments qui satisfont le prédicat. Dans le `main()`, nous utilisons la méthode `filter()` pour filtrer les nombres pairs d'une liste d'entiers.


**Exercice 21 :**
```java
public class GenericsExercise1 {

    public static void main(String[] args) {
        Box<Integer> intBox = new Box<>();
        intBox.set("Hello");
        
        System.out.println(intBox.get());
    }
}

class Box<T> {
    private T value;

    public void set(T value) {
        this.value = value;
    }

    public T get() {
        return value;
    }
}
```
**Solution :** Le code ne compile pas en raison d'une incompatibilité de types. La classe `Box` est déclarée avec le type générique `T` et la variable `value` est également de type `T`. Dans cet exercice, nous essayons de définir une valeur de type `String` dans une `Box<Integer>`, ce qui entraîne une erreur de compilation.

**Exercice 22 :**
```java
public class GenericsExercise2 {

    public static void main(String[] args) {
        Box<String> strBox = new Box<>();
        strBox.set(10);
        
        System.out.println(strBox.get());
    }
}

class Box<T> {
    private T value;

    public void set(T value) {
        this.value = value;
    }

    public T get() {
        return value;
    }
}
```
**Solution :** Le code ne compile pas en raison d'une incompatibilité de types. Dans cet exercice, nous essayons de définir une valeur de type `Integer` dans une `Box<String>`, ce qui entraîne une erreur de compilation.

**Exercice 23 :**
```java
public class GenericsExercise3 {

    public static void main(String[] args) {
        List<?> list = new ArrayList<>();
        list.add("Hello");
        
        System.out.println(list.get(0));
    }
}
```
**Solution :** Le code ne compile pas. L'utilisation de l'opérateur wildcard (`?`) dans la déclaration de la liste indique un type inconnu, ce qui signifie que nous ne pouvons pas ajouter d'éléments à cette liste. La méthode `add()` génère une erreur de compilation.

**Exercice 24 :**
```java
public class GenericsExercise4 {

    public static void main(String[] args) {
        List<Number> numbers = new ArrayList<Integer>();
        numbers.add(10);
        
        System.out.println(numbers.get(0));
    }
}
```
**Solution :** Le code ne compile pas en raison d'une incompatibilité de types. La déclaration de `numbers` indique qu'il s'agit d'une liste de `Number`, mais nous essayons de l'initialiser avec une `ArrayList<Integer>`. Les types génériques ne sont pas covariants en Java, donc cette assignation est invalide et génère une erreur de compilation.

**Exercice 25 :**
```java
public class GenericsExercise5 {

    public static void main(String[] args) {
        List<Number> numbers = new ArrayList<>();
        numbers.add(10);
        
        List<Integer> integers = numbers;
        
        System.out.println(integers.get(0));
    }
}
```
**Solution :** Le code ne compile pas en raison d'une incompatibilité de types. Nous essayons d'assigner une `List<Number>` à une `List<Integer>`, ce qui génère une erreur de compilation. Les types génériques ne sont pas covariants en

 Java.

**Exercice 26 :**
```java
public class GenericsExercise6<T> {

    public static void main(String[] args) {
        GenericsExercise6<String> ex = new GenericsExercise6<>();
        ex.<String>print("Hello");
    }
    
    public <T> void print(T value) {
        System.out.println(value);
    }
}
```
**Solution :** Le code compile sans erreur. La classe `GenericsExercise6` est instanciée avec le type générique `String`. La méthode `print` est une méthode générique qui peut prendre n'importe quel type. Dans cet exercice, nous utilisons explicitement le type générique `<String>` lors de l'appel de la méthode `print`.

**Exercice 27 :**
```java
public class GenericsExercise7 {

    public static void main(String[] args) {
        List<String> strings = new ArrayList<>();
        strings.add("Hello");
        
        List<Object> objects = strings;
        objects.add(10);
        
        System.out.println(strings.get(1));
    }
}
```
**Solution :** Le code compile sans erreur. Nous assignons une `List<String>` à une `List<Object>`, ce qui est autorisé en Java. Cependant, cela permet également d'ajouter des éléments de type `Integer` à la `List<String>`. Dans cet exercice, nous ajoutons un entier à `strings`, et l'appel de `strings.get(1)` renvoie cet entier.

**Exercice 28 :**
```java
public class GenericsExercise8<T extends Number> {

    public static void main(String[] args) {
        GenericsExercise8<String> ex = new GenericsExercise8<>();
        ex.print("Hello");
    }
    
    public void print(T value) {
        System.out.println(value);
    }
}
```
**Solution :** Le code ne compile pas en raison d'une incompatibilité de types. La classe `GenericsExercise8` est déclarée avec une contrainte de type générique `T extends Number`. Dans cet exercice, nous essayons d'instancier `GenericsExercise8` avec le type `String`, qui ne satisfait pas la contrainte de type.

**Exercice 29 :**
```java
public class GenericsExercise9 {

    public static void main(String[] args) {
        List<?> list = new ArrayList<>();
        list.add("Hello");
        
        System.out.println(list.get(0).length());
    }
}
```
**Solution :** Le code ne compile pas. L'utilisation de l'opérateur wildcard (`?`) dans la déclaration de la liste indique un type inconnu, ce qui signifie que nous ne pouvons pas accéder aux méthodes spécifiques d'un type particulier. Dans cet exercice, nous essayons d'appeler la méthode `length()` sur un élément de la liste, ce qui génère une erreur de compilation.

**Exercice 30 :**
```java
public class GenericsExercise10 {

    public static void main(String[] args) {
        List<?> list = new ArrayList<>();
        list.add(10);
        
        System.out.println(list.get(0));
    }
}
```
**Solution :** Le code ne compile pas. L'utilisation de l'opérateur wildcard (`?`) dans la déclaration de la liste indique un type inconnu, ce qui signifie que nous ne pouvons pas ajouter d'éléments à cette liste. La méthode `add()` génère une erreur de compilation.
