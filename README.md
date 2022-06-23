# Learning-Blockchain
## We will be creating our own local Blockchain, just like a bitcoin we will create our own 'MidNightCoin'.
But first let's talk a bit about Blockchain.
### So what exactly is a Blockchain? ###
Concatenation of multiple blocks containing information about a particular set of similar transactions that are interlinked to one another via a chain of hash values, each new block corresponding to the 'Hash value' of its previous block.
### That would do for the bookish definition of Blockchain ###
In layman's language, a Blockchain is just like a reversed LinkedList with elements bound in a chain, each corresponding to its previous elememts for its verification.
### How is a Blockchain secured? ###
A block is very secured if it comes to illegal tampering with/of one or more blocks related to it.
There are basically three security measures in Blockchain:
<li>The Hash values</li>
<li>The Proof Of Work </li>
<li>The Endorsement </li>

#### The Hash Values ####
Each block in a Blockchain has a very specific and unique 'Hash' data associated with it. When a new block is added to the BlockChain, It gets its own 'Hash' data but it also stores and corresponds to its previous block's 'Hash' and so on. This way even if someone tampers with even one block in any manner, the Hash data of all the corresponding next blocks and The whole blockchain gets disrupted, otherwise gets changed.

#### The Proof of Work ####

Sometimes, the malicious agents get past the Hash value security of the BlockChain, This is because modern day computers are very efficient and powerful. Then 'The Proof Of Work' comes into play, it is more like an evidence regarding the changes that someone has created that has to be submitted as a PoW to the Endorsing agents.

#### The Endorsement ####

Finally once the changes have been committed, and the Proof Of Work has been generated, a group of owning bodies/individuals called "Endorsers" take up on a vote to decide whenther or not to grant acceptance to the changes, normally a majority vote is needed for a change to be accepted.

# You will be required to install the "requirements.txt" file to code/edit/run the BlockChain codes #
Now having read enough, you will need to install the VS Code C++ and python3 for 64-bit.

Use the following links to do the same:

https://code.visualstudio.com/Download

https://www.python.org/ftp/python/3.10.2/python-3.10.2-amd64.exe

Once installed, open your command prompt and enter the following commands:

pip install -r requirements.txt
This may take several minutes to install, once done open the code in the VS Code Editor and continue with the code.

