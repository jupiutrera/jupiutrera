# Juan Utrera

Applied AI engineer. I build multi-agent coding workflows and the evals that tell me whether they work.

## Selected work

| Project | What it is | Measured |
|---|---|---|
| [**open-chess**](https://github.com/jupiutrera/open-chess) | A free chess training app for web and Android, written mostly by coding agents under a written rule file and CI gates. [How it is built](https://github.com/jupiutrera/open-chess/blob/main/docs/built-with-agents.md). | 19k lines of TypeScript, 42 unit test files and 17 end-to-end flows, 47 merged PRs and 16 releases in its first three weeks. |
| [**lichess-mcp**](https://github.com/jupiutrera/lichess-mcp) | An MCP server that gives a coding agent read-only access to Lichess: players, games, engine evaluations, opening statistics, endgame tablebases. | 20 questions graded against the live API: 20/20 with the server against 5/20 (Sonnet 5.5) and 2/20 (Haiku 5.5) with no tools. |
| [**laya-vs-jev**](https://github.com/jupiutrera/laya-vs-jev) | A calibration eval: when a model says 90 %, is it right 9 times out of 10? Three models, the same 2,000 decisions, every raw answer stored. | ECE of 0.036, 0.175 and 0.213 as shipped. The same answers score from 0.021 to 0.169 depending on how ECE is computed. Recomputed in CI. |
| [**kartlab**](https://github.com/jupiutrera/kartlab) | A kart that learns to drive with PPO on procedurally generated tracks, with a 16-bit style viewer. CPU only. | 1.5M steps in about 20 minutes on a laptop; 3 clean laps on all 20 held-out tracks. |

## Contact

[LinkedIn](https://www.linkedin.com/in/juanutrera)
