NEO Unit Tests
====================

Dieses Projekt ist in Arbeit und zielt darauf ab, Unit-Test-Coverage für den Core-NEO-Code bereitzustellen.

Bitte beachten Sie, dass wir uns bewusst sind, dass wir in diesen Tests keine geeigneten Techniken zu Isolation / Dependency Injection / Mocking verwenden. Um dies zu tun, wären größere Nachbearbeitungen des Basiscodes erforderlich, was eine Änderung für einen späteren Zeitpunkt im Gespräch mit dem Core-Team darstellt. Im Moment wollen wir nur eine Grunddeckung erreichen.

Struktur
====================

Wir verwenden integrierte Visual Studio-Funktionalität mit MSTest und dem Microsoft.VisualStudio.TestPlatform.TestFramework package.

Um die Tests auszuführen, erstellen Sie die Lösung, um Tests zu erkennen, und zeigen Sie dann die Tests im Fenster "Test Explorer" in Visual Studio an und führen Sie sie aus.
ODER
Wenn das .NET Core SDK installiert ist, navigieren Sie mithilfe der CLI zum Ordner neo.UnitTest und verwenden Sie den Befehl "dotnet restore", um Pakete abzurufen, gefolgt von "dotnet test", um Tests auszuführen.

Abdeckung
====================

* Base
	* Fixed8.cs
* Core
	* AccountState.cs
	* AssetState.cs
	* Block.cs - Some code coverage missing on the Verify() method.
	* ClaimTransaction.cs	
	* CoinReference.cs	
	* Header.cs
	* Helper.cs
	* InvocationTransaction.cs
	* IssueTransaction.cs
	* MinerTransaction.cs
	* SpentCoin.cs
	* SpentCoinState.cs
	* StorageItem.cs
	* StorageKey.cs
	* TransactionAttribute.cs
	* TransactionOuput.cs
	* TransactionResult.cs
	* UnspentCoinState.cs
	* ValidatorState.cs
	* VoteState.cs
	* Witness.cs


