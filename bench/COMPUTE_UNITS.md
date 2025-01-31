# Compute Units

All notable changes in compute units usage will be documented in this file.

The changes are calculated by comparing the current results with the last version's results. Increase in usage is shown with 🔴 and decrease is shown with 🟢.

The programs and their tests are located in [/tests/bench](https://github.com/coral-xyz/anchor/tree/master/tests/bench).

> **Note**
> Results documented in this file are autogenerated. Running the tests will update the current results when necessary, manually editing the results should be avoided.

> **Warning**
> Results may vary depending on Solana version.

## [Unreleased]

Solana version: 1.16.0

| Instruction                 | Compute Units | +/-               |
| --------------------------- | ------------- | ----------------- |
| accountInfo1                | 1,015         | -                 |
| accountInfo2                | 1,475         | -                 |
| accountInfo4                | 1,964         | -                 |
| accountInfo8                | 3,841         | -                 |
| accountEmptyInit1           | 5,817         | -                 |
| accountEmpty1               | 1,149         | -                 |
| accountEmptyInit2           | 10,402        | -                 |
| accountEmpty2               | 1,754         | -                 |
| accountEmptyInit4           | 19,508        | -                 |
| accountEmpty4               | 2,540         | -                 |
| accountEmptyInit8           | 37,265        | -                 |
| accountEmpty8               | 5,016         | -                 |
| accountSizedInit1           | 5,924         | -                 |
| accountSized1               | 1,214         | -                 |
| accountSizedInit2           | 10,680        | -                 |
| accountSized2               | 1,873         | -                 |
| accountSizedInit4           | 19,970        | -                 |
| accountSized4               | 2,762         | -                 |
| accountSizedInit8           | 38,122        | -                 |
| accountSized8               | 5,353         | -                 |
| accountUnsizedInit1         | 6,052         | -                 |
| accountUnsized1             | 1,338         | -                 |
| accountUnsizedInit2         | 10,929        | -                 |
| accountUnsized2             | 1,778         | -                 |
| accountUnsizedInit4         | 20,339        | -                 |
| accountUnsized4             | 3,136         | -                 |
| accountUnsizedInit8         | 39,096        | -                 |
| accountUnsized8             | 5,952         | -                 |
| boxedAccountEmptyInit1      | 6,034         | -                 |
| boxedAccountEmpty1          | 888           | -                 |
| boxedAccountEmptyInit2      | 10,633        | -                 |
| boxedAccountEmpty2          | 1,401         | -                 |
| boxedAccountEmptyInit4      | 19,311        | -                 |
| boxedAccountEmpty4          | 2,424         | -                 |
| boxedAccountEmptyInit8      | 37,136        | -                 |
| boxedAccountEmpty8          | 4,659         | -                 |
| boxedAccountSizedInit1      | 6,130         | -                 |
| boxedAccountSized1          | 917           | -                 |
| boxedAccountSizedInit2      | 10,828        | -                 |
| boxedAccountSized2          | 1,463         | -                 |
| boxedAccountSizedInit4      | 19,703        | -                 |
| boxedAccountSized4          | 2,543         | -                 |
| boxedAccountSizedInit8      | 37,919        | -                 |
| boxedAccountSized8          | 4,898         | -                 |
| boxedAccountUnsizedInit1    | 6,240         | -                 |
| boxedAccountUnsized1        | 972           | -                 |
| boxedAccountUnsizedInit2    | 11,048        | -                 |
| boxedAccountUnsized2        | 1,570         | -                 |
| boxedAccountUnsizedInit4    | 20,138        | -                 |
| boxedAccountUnsized4        | 2,768         | -                 |
| boxedAccountUnsizedInit8    | 38,791        | 🟢 **-9 (0.02%)** |
| boxedAccountUnsized8        | 5,347         | -                 |
| boxedInterfaceAccountMint1  | 2,296         | -                 |
| boxedInterfaceAccountMint2  | 4,129         | -                 |
| boxedInterfaceAccountMint4  | 7,783         | -                 |
| boxedInterfaceAccountMint8  | 15,281        | -                 |
| boxedInterfaceAccountToken1 | 2,023         | -                 |
| boxedInterfaceAccountToken2 | 3,582         | -                 |
| boxedInterfaceAccountToken4 | 6,692         | -                 |
| boxedInterfaceAccountToken8 | 13,098        | -                 |
| interfaceAccountMint1       | 2,364         | -                 |
| interfaceAccountMint2       | 5,030         | -                 |
| interfaceAccountMint4       | 9,803         | -                 |
| interfaceAccountMint8       | 18,400        | -                 |
| interfaceAccountToken1      | 2,091         | -                 |
| interfaceAccountToken2      | 3,948         | -                 |
| interfaceAccountToken4      | 7,547         | -                 |
| interface1                  | 1,059         | -                 |
| interface2                  | 1,479         | -                 |
| interface4                  | 1,900         | -                 |
| interface8                  | 3,646         | -                 |
| program1                    | 1,053         | -                 |
| program2                    | 1,467         | -                 |
| program4                    | 1,878         | -                 |
| program8                    | 3,598         | -                 |
| signer1                     | 1,018         | -                 |
| signer2                     | 1,484         | -                 |
| signer4                     | 1,984         | -                 |
| signer8                     | 3,880         | -                 |
| systemAccount1              | 1,072         | -                 |
| systemAccount2              | 1,590         | -                 |
| systemAccount4              | 2,195         | -                 |
| systemAccount8              | 4,305         | -                 |
| uncheckedAccount1           | 1,014         | -                 |
| uncheckedAccount2           | 1,475         | -                 |
| uncheckedAccount4           | 1,965         | -                 |
| uncheckedAccount8           | 3,841         | -                 |

### Notable changes

---

## [0.28.0]

Solana version: 1.16.0

| Instruction                 | Compute Units | +/-                    |
| --------------------------- | ------------- | ---------------------- |
| accountInfo1                | 1,015         | 🔴 **+61 (6.39%)**     |
| accountInfo2                | 1,475         | 🟢 **-92 (5.87%)**     |
| accountInfo4                | 1,964         | 🟢 **-95 (4.61%)**     |
| accountInfo8                | 3,841         | 🟢 **-15 (0.39%)**     |
| accountEmptyInit1           | 5,817         | 🟢 **-141 (2.37%)**    |
| accountEmpty1               | 1,149         | 🔴 **+59 (5.41%)**     |
| accountEmptyInit2           | 10,402        | 🟢 **-172 (1.63%)**    |
| accountEmpty2               | 1,754         | 🟢 **-98 (5.29%)**     |
| accountEmptyInit4           | 19,508        | 🟢 **-49 (0.25%)**     |
| accountEmpty4               | 2,540         | 🟢 **-106 (4.01%)**    |
| accountEmptyInit8           | 37,265        | 🟢 **-276 (0.74%)**    |
| accountEmpty8               | 5,016         | 🟢 **-27 (0.54%)**     |
| accountSizedInit1           | 5,924         | 🟢 **-139 (2.29%)**    |
| accountSized1               | 1,214         | 🔴 **+79 (6.96%)**     |
| accountSizedInit2           | 10,680        | 🟢 **-103 (0.96%)**    |
| accountSized2               | 1,873         | 🟢 **-93 (4.73%)**     |
| accountSizedInit4           | 19,970        | 🟢 **-5 (0.03%)**      |
| accountSized4               | 2,762         | 🟢 **-25 (0.90%)**     |
| accountSizedInit8           | 38,122        | 🟢 **-259 (0.67%)**    |
| accountSized8               | 5,353         | 🟢 **-6 (0.11%)**      |
| accountUnsizedInit1         | 6,052         | 🟢 **-141 (2.28%)**    |
| accountUnsized1             | 1,338         | 🔴 **+95 (7.64%)**     |
| accountUnsizedInit2         | 10,929        | 🟢 **-113 (1.02%)**    |
| accountUnsized2             | 1,778         | 🟢 **-115 (6.08%)**    |
| accountUnsizedInit4         | 20,339        | 🟢 **-156 (0.76%)**    |
| accountUnsized4             | 3,136         | 🔴 **+32 (1.03%)**     |
| accountUnsizedInit8         | 39,096        | 🟢 **-323 (0.82%)**    |
| accountUnsized8             | 5,952         | 🟢 **-99 (1.64%)**     |
| boxedAccountEmptyInit1      | 6,034         | 🟢 **-126 (2.05%)**    |
| boxedAccountEmpty1          | 888           | 🟢 **-88 (9.02%)**     |
| boxedAccountEmptyInit2      | 10,633        | 🟢 **-151 (1.40%)**    |
| boxedAccountEmpty2          | 1,401         | 🟢 **-98 (6.54%)**     |
| boxedAccountEmptyInit4      | 19,311        | 🟢 **-189 (0.97%)**    |
| boxedAccountEmpty4          | 2,424         | 🟢 **-106 (4.19%)**    |
| boxedAccountEmptyInit8      | 37,136        | 🟢 **-279 (0.75%)**    |
| boxedAccountEmpty8          | 4,659         | 🟢 **-121 (2.53%)**    |
| boxedAccountSizedInit1      | 6,130         | 🟢 **-126 (2.01%)**    |
| boxedAccountSized1          | 917           | 🟢 **-86 (8.57%)**     |
| boxedAccountSizedInit2      | 10,828        | 🟢 **-147 (1.34%)**    |
| boxedAccountSized2          | 1,463         | 🟢 **-91 (5.86%)**     |
| boxedAccountSizedInit4      | 19,703        | 🟢 **-181 (0.91%)**    |
| boxedAccountSized4          | 2,543         | 🟢 **-99 (3.75%)**     |
| boxedAccountSizedInit8      | 37,919        | 🟢 **-263 (0.69%)**    |
| boxedAccountSized8          | 4,898         | 🟢 **-105 (2.10%)**    |
| boxedAccountUnsizedInit1    | 6,240         | 🟢 **-134 (2.10%)**    |
| boxedAccountUnsized1        | 972           | 🟢 **-97 (9.07%)**     |
| boxedAccountUnsizedInit2    | 11,048        | 🟢 **-163 (1.45%)**    |
| boxedAccountUnsized2        | 1,570         | 🟢 **-109 (6.49%)**    |
| boxedAccountUnsizedInit4    | 20,138        | 🟢 **-213 (1.05%)**    |
| boxedAccountUnsized4        | 2,768         | 🟢 **-131 (4.52%)**    |
| boxedAccountUnsizedInit8    | 38,800        | 🟢 **-318 (0.81%)**    |
| boxedAccountUnsized8        | 5,347         | 🟢 **-170 (3.08%)**    |
| boxedInterfaceAccountMint1  | 2,296         | 🟢 **-3 (0.13%)**      |
| boxedInterfaceAccountMint2  | 4,129         | 🔴 **+76 (1.88%)**     |
| boxedInterfaceAccountMint4  | 7,783         | 🔴 **+245 (3.25%)**    |
| boxedInterfaceAccountMint8  | 15,281        | 🔴 **+582 (3.96%)**    |
| boxedInterfaceAccountToken1 | 2,023         | 🔴 **+286 (16.47%)**   |
| boxedInterfaceAccountToken2 | 3,582         | 🔴 **+654 (22.34%)**   |
| boxedInterfaceAccountToken4 | 6,692         | 🔴 **+1,401 (26.48%)** |
| boxedInterfaceAccountToken8 | 13,098        | 🔴 **+2,893 (28.35%)** |
| interfaceAccountMint1       | 2,364         | 🟢 **-166 (6.56%)**    |
| interfaceAccountMint2       | 5,030         | 🔴 **+304 (6.43%)**    |
| interfaceAccountMint4       | 9,803         | 🔴 **+372 (3.94%)**    |
| interfaceAccountMint8       | 18,400        | 🔴 **+691 (3.90%)**    |
| interfaceAccountToken1      | 2,091         | 🔴 **+336 (19.15%)**   |
| interfaceAccountToken2      | 3,948         | 🔴 **+737 (22.95%)**   |
| interfaceAccountToken4      | 7,547         | 🔴 **+1,541 (25.66%)** |
| interface1                  | 1,059         | 🔴 **+60 (6.01%)**     |
| interface2                  | 1,479         | 🟢 **-95 (6.04%)**     |
| interface4                  | 1,900         | 🟢 **-96 (4.81%)**     |
| interface8                  | 3,646         | 🟢 **-5 (0.14%)**      |
| program1                    | 1,053         | 🔴 **+54 (5.41%)**     |
| program2                    | 1,467         | 🟢 **-106 (6.74%)**    |
| program4                    | 1,878         | 🟢 **-120 (6.01%)**    |
| program8                    | 3,598         | 🟢 **-53 (1.45%)**     |
| signer1                     | 1,018         | 🔴 **+60 (6.26%)**     |
| signer2                     | 1,484         | 🟢 **-92 (5.84%)**     |
| signer4                     | 1,984         | 🟢 **-95 (4.57%)**     |
| signer8                     | 3,880         | 🟢 **-15 (0.39%)**     |
| systemAccount1              | 1,072         | 🔴 **+59 (5.82%)**     |
| systemAccount2              | 1,590         | 🟢 **-96 (5.69%)**     |
| systemAccount4              | 2,195         | 🟢 **-103 (4.48%)**    |
| systemAccount8              | 4,305         | 🟢 **-31 (0.71%)**     |
| uncheckedAccount1           | 1,014         | 🔴 **+61 (6.40%)**     |
| uncheckedAccount2           | 1,475         | 🟢 **-92 (5.87%)**     |
| uncheckedAccount4           | 1,965         | 🟢 **-95 (4.61%)**     |
| uncheckedAccount8           | 3,841         | 🟢 **-14 (0.36%)**     |

### Notable changes

- Upgrading Solana to `1.16`. The difference in compute units usage between `0.27.0` and `0.28.0` is the direct result of upgrading Solana version(both build tools and crates) ([#2512](https://github.com/coral-xyz/anchor/pull/2512)).

---

## [0.27.0]

Solana version: 1.14.16

| Instruction                 | Compute Units | +/- |
| --------------------------- | ------------- | --- |
| accountInfo1                | 954           | N/A |
| accountInfo2                | 1,567         | N/A |
| accountInfo4                | 2,059         | N/A |
| accountInfo8                | 3,856         | N/A |
| accountEmptyInit1           | 5,958         | N/A |
| accountEmpty1               | 1,090         | N/A |
| accountEmptyInit2           | 10,574        | N/A |
| accountEmpty2               | 1,852         | N/A |
| accountEmptyInit4           | 19,557        | N/A |
| accountEmpty4               | 2,646         | N/A |
| accountEmptyInit8           | 37,541        | N/A |
| accountEmpty8               | 5,043         | N/A |
| accountSizedInit1           | 6,063         | N/A |
| accountSized1               | 1,135         | N/A |
| accountSizedInit2           | 10,783        | N/A |
| accountSized2               | 1,966         | N/A |
| accountSizedInit4           | 19,975        | N/A |
| accountSized4               | 2,787         | N/A |
| accountSizedInit8           | 38,381        | N/A |
| accountSized8               | 5,359         | N/A |
| accountUnsizedInit1         | 6,193         | N/A |
| accountUnsized1             | 1,243         | N/A |
| accountUnsizedInit2         | 11,042        | N/A |
| accountUnsized2             | 1,893         | N/A |
| accountUnsizedInit4         | 20,495        | N/A |
| accountUnsized4             | 3,104         | N/A |
| accountUnsizedInit8         | 39,419        | N/A |
| accountUnsized8             | 6,051         | N/A |
| boxedAccountEmptyInit1      | 6,160         | N/A |
| boxedAccountEmpty1          | 976           | N/A |
| boxedAccountEmptyInit2      | 10,784        | N/A |
| boxedAccountEmpty2          | 1,499         | N/A |
| boxedAccountEmptyInit4      | 19,500        | N/A |
| boxedAccountEmpty4          | 2,530         | N/A |
| boxedAccountEmptyInit8      | 37,415        | N/A |
| boxedAccountEmpty8          | 4,780         | N/A |
| boxedAccountSizedInit1      | 6,256         | N/A |
| boxedAccountSized1          | 1,003         | N/A |
| boxedAccountSizedInit2      | 10,975        | N/A |
| boxedAccountSized2          | 1,554         | N/A |
| boxedAccountSizedInit4      | 19,884        | N/A |
| boxedAccountSized4          | 2,642         | N/A |
| boxedAccountSizedInit8      | 38,182        | N/A |
| boxedAccountSized8          | 5,003         | N/A |
| boxedAccountUnsizedInit1    | 6,374         | N/A |
| boxedAccountUnsized1        | 1,069         | N/A |
| boxedAccountUnsizedInit2    | 11,211        | N/A |
| boxedAccountUnsized2        | 1,679         | N/A |
| boxedAccountUnsizedInit4    | 20,351        | N/A |
| boxedAccountUnsized4        | 2,899         | N/A |
| boxedAccountUnsizedInit8    | 39,118        | N/A |
| boxedAccountUnsized8        | 5,517         | N/A |
| boxedInterfaceAccountMint1  | 2,299         | N/A |
| boxedInterfaceAccountMint2  | 4,053         | N/A |
| boxedInterfaceAccountMint4  | 7,538         | N/A |
| boxedInterfaceAccountMint8  | 14,699        | N/A |
| boxedInterfaceAccountToken1 | 1,737         | N/A |
| boxedInterfaceAccountToken2 | 2,928         | N/A |
| boxedInterfaceAccountToken4 | 5,291         | N/A |
| boxedInterfaceAccountToken8 | 10,205        | N/A |
| interfaceAccountMint1       | 2,530         | N/A |
| interfaceAccountMint2       | 4,726         | N/A |
| interfaceAccountMint4       | 9,431         | N/A |
| interfaceAccountMint8       | 17,709        | N/A |
| interfaceAccountToken1      | 1,755         | N/A |
| interfaceAccountToken2      | 3,211         | N/A |
| interfaceAccountToken4      | 6,006         | N/A |
| interface1                  | 999           | N/A |
| interface2                  | 1,574         | N/A |
| interface4                  | 1,996         | N/A |
| interface8                  | 3,651         | N/A |
| program1                    | 999           | N/A |
| program2                    | 1,573         | N/A |
| program4                    | 1,998         | N/A |
| program8                    | 3,651         | N/A |
| signer1                     | 958           | N/A |
| signer2                     | 1,576         | N/A |
| signer4                     | 2,079         | N/A |
| signer8                     | 3,895         | N/A |
| systemAccount1              | 1,013         | N/A |
| systemAccount2              | 1,686         | N/A |
| systemAccount4              | 2,298         | N/A |
| systemAccount8              | 4,336         | N/A |
| uncheckedAccount1           | 953           | N/A |
| uncheckedAccount2           | 1,567         | N/A |
| uncheckedAccount4           | 2,060         | N/A |
| uncheckedAccount8           | 3,855         | N/A |

---
