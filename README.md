# eSecureVote

## Repository Note

This repository is my personal portfolio-preserved fork of a collaborative academic project.

It is maintained as a reference to preserve the project's source code and development history. I am not claiming sole ownership or authorship of the complete application.

My individual contributions can be reviewed through my author-filtered Git commit history.

Original repository: [christinedln/eSecureVote](https://github.com/christinedln/eSecureVote)

My contributions: [Commits authored by yuanenriquez](https://github.com/yuanenriquez/eSecureVote/commits/main/?author=yuanenriquez)

## Project Overview

eSecureVote was a collaborative academic electronic-voting application developed by Computer Science students. The project explored digital voting workflows, ballot and election-result processing, encryption, Firebase Firestore integration, and audit logging.

This repository is a preserved academic project, not a production-ready election system. The original project description includes intended goals and features; it should not be read as a guarantee that every proposed feature was fully implemented, tested, or security-audited.

## My Contributions

My individual work, as reflected in the author-filtered commit history, included:

- Contributing to ballot and election-result processing logic.
- Implementing and refining AES-EAX-based ballot/vote decryption and result-encryption functions.
- Working on Firebase Firestore-backed audit logging and log retrieval.
- Prototyping administrative access-check logic.
- Writing Python unit tests with `unittest` and `unittest.mock` (including `MagicMock`) for Firestore audit-log retrieval scenarios.

**Testing note:** The audit-log test file I authored was later removed during repository cleanup. The commit history preserves evidence of that work, but the test file is not present in the current repository tree.

These were contributions to a team project. I am not claiming sole authorship of the application or the complete voting/encryption architecture.

## Technologies and Concepts

- Python
- Firebase Admin SDK / Firestore
- AES-EAX-based encryption and decryption code
- Python `unittest` and `unittest.mock`

## Project Limitations

This is an academic prototype and should not be used to conduct real elections or store real voter information. Its code has not been presented as a production security implementation or an independently audited voting system. Review the source and project history before drawing conclusions about the completeness or security of any feature.
