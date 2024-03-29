
# DeVault Development Blog since Testnet Launch

July 27

* Add unlock wallet to menu
* Add reveal word phrase to menu
* Integrate/review new word phrase GUI update, that allows restoring 12 or 24 word phrase wallets as well as automating process to check user has written down initial phrase for new wallets
* Fix cmake compile for Catalina on MacOS
* Fix deprecated QT code
* Add filtering options for transactions to show Rewards/Budgets
* Created Breadwallet iOS DeVault clone that can send/receive transactions
* Worked on ElectronCash DeVault clone and integrated DeVault functionality to allow rx/tx transactions
* Tested iphone version of ElectronCash clone for DeVault
* various other changes/fixes


July 20

* Added RPC command `getdifficulties` to allow examining average block times and difficulty changes over time
* std::filesystem fixes
* update getrewardinfo
* worked on BreadWallet IOS app and Electron Cash clone

July 13

* Add ability to use 24 word phrases from command line for new wallets
* Several upstream merge commits
* Fix/update several unit tests
* Fix consensus issue whereby client halted rather than rejecting invalid incoming blocks and continuing on
* Added getrewardinfo RPC command
* Upgraded QT code to avoid deprecated warning

July 6

* Setup all unit tests to use cmake/ctest/catch2


June 29

* Refactoring wallet for HDChain handling and other stuff
* Change unit test setup to use cmake/ctest
* Added support for 24 word mnemonics
* Various ABC updates

June 22

* Better handling version info for CMake builds + updated comments
* Fixed cmake unit tests
* Add a class to allow timing code/functions
* Various ABC updates
* add to display estimated reward block for getmyrewardinfo
* Handle negative amounts properly in amount::ToString() and other amount changes
* add code to check for updated releases in client

June 15

* More refactoring of Amount class & related code.
* Discovered and fixed issue that would have led to large % errors in some reward amounts
* Update unit tests
* Removed dead code
* Fix builds without wallet (ENABLE_WALLET) for non-QT targets
* Pull in about 90-100 bitcoin/bitcoin-abc updates
* Fix issue with getmyrewardinfo showing wrong estimated dates


June 8

* Reworked amount class related code
* Refactor Mnemonic code as setup for GUI based entry/checking
* Bug fix for RPC FormatMoney output
* Various other code fixes


June 1

* Added ability for CMake to build DMG properly for MacOS
* Cleanup removing some redundant files used for Mnemonic processing
* Added documentation, include Checklist and ReOrg test plan
* Push out hard-fork in code so it doesn't trigger unintendedly
* Added `getmyrewardinfo` which tells useers when they can expect Cold Rewards
* Handle rewards processing to lessen memory/database load
* Took about 30 updates from Bitcoin ABCs code base for merge
* Removed Unneeded Service bits

