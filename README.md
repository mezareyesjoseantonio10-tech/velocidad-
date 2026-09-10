# velocidad-
gamer 
| 1 | Auto-Recall on SessionStart | M | SUPERSEDED | 已被 `teamai-recall` subagent + builtin-rules 主动检索替代 |export function buildSkillZip(slug: string, files: Record<string, string> = {}): Uint8Array { 
 export function buildSkillZip( 
   slug: string, 
   files: Record<string, string> = {}, 
   opts: { name?: string } = {}, 
 ): Uint8Array { 
   const skillName = opts.name ?? slug; 
    const entries: Record<string, Uint8Array> = { 
     [`${slug}/SKILL.md`]: strToU8(`---\nname: ${slug}\nversion: 1.0.0\ndescription: mock\n---\nbody`),Understanding GitHub Code Search syntaxninja -vC build doc/html