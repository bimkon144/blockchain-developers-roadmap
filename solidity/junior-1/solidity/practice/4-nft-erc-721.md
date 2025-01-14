# NFT-721

- Пройти [Lesson 14: Hardhat ERC20s](https://github.com/smartcontractkit/full-blockchain-solidity-course-js#lesson-14-hardhat-nfts-everything-you-need-to-know-about-nfts)

Критерии прохождения задания:
 - Изучить стандарт ERC-721, разобрать все основные методы.
 - Написать простой ERC-721 с использованием OpenZeppelin библиотеки.
 - Деплой смарт-контрактов в тестовую сеть.
 - Написать тесты для смарт-контрактов.
 - Понять как работают ERC-721.
 - Пройтись по литературе на которую приведены ссылки.

Дополнительно:

 - Загрузить картинки токенов и метаданные токенов в IPFS используя pinata.
 - Попробовать написать скрипты для програмной загрузки файлов на ipfs.
 - Попробовать запустить свою ноду ipfs.
 - Попробовать использовать другие расширения ERC-721 от OpenZeppelin.

        
## Какие навыки даст задание?

1. Понимание общего принципа работы стандарта NFT-721 и его дополнений.
2. Понимание, что такое протоколы с распределенной файловой системой и как с ними работать.


## Вопросы по теории:

1. Что такое NFT? Какие главные отличия от ERC-20?
2. Что такое token URI и как можно его задавать? 
3. Что такое IPFS и в чем его отличия от Pinata, nft.storage? Какие преумущества и недостатки?
4. Что такое метаданные?
5. Можно ли загружать метаданные прямиком в блокчейн? Какие преймущества и недостатки?
6. Какие методы должны быть в токене ERC-721? Что они делают?
7. Какие расширения ERC-721 есть у OpenZeppelin?
8. Какие недостатки есть у ERC-721?
9. Зачем нужны хуки `_beforeTokenTransfer` и `_afterTokenTransfer`? В каких методах ERC-721 они используются?
10. Расширения ERC-721, Какой функционал добавляют следующие расширения:
    - ERC721Pausable
    - ERC721Burnable
    - ERC721Consecutive
    - ERC721URIStorage
    - ERC721Votes
    - ERC721Royalty
    - ERC721Enumerable
11. Каким образом можно получить все нфт которыми владеет пользователь? Какое дополнение нужно использовать?


### Литература:

- [ERC-721 standart](https://ethereum.org/en/developers/docs/standards/tokens/erc-721/)
- [EIP-721](https://eips.ethereum.org/EIPS/eip-721)
- [Набор контрактов и утилит ERC-721 от OpenZeppelin](https://docs.openzeppelin.com/contracts/4.x/erc721)
- [ERC-721 Github OpenZeppelin](https://github.com/OpenZeppelin/openzeppelin-contracts/tree/master/contracts/token/ERC721)
- [ERC-721 tutorial](https://www.youtube.com/watch?v=YwXXLmRZI3Y&ab_channel=BlockchainBob)
- [ERC-721 URI Storage tutorial](https://www.youtube.com/watch?v=NU5Z-NIK4_U&ab_channel=BlockchainBob)
- [ERC-721 Enumirable tutorial](https://www.youtube.com/watch?v=hL5uPgEAuIo&ab_channel=BlockchainBob)
- [OpenZeppeling Wizard](https://docs.openzeppelin.com/contracts/4.x/wizard)
- [Etherscan tracker NFT](https://etherscan.io/tokens-nft)
- [Приятный бонус - NFT-721A](https://www.erc721a.org/)
