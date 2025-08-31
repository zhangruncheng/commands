Save current project context for future agent coordination: # 为未来的晿能体协调保存当前项目上下文：

[Extended thinking: This tool uses the context-manager agent to capture and preserve project state, decisions, and patterns. This enables better continuity across sessions and improved agent coordination.] # [扩展思维：该工具使用上下文管理器晿能体来捕获和保存项目状态、决策和模式。这实现了更好的跨会话连续性和改善的晿能体协调。]

## Context Capture Process # 上下文捕获流程

Use Task tool with subagent_type="context-manager" to save comprehensive project context. # 使用任务工具，子晿能体类型为"context-manager"来保存全面的项目上下文。

Prompt: "Save comprehensive project context for: $ARGUMENTS. Capture: # 提示："为$ARGUMENTS保存全面的项目上下文。捕获：

1. **Project Overview**
   - Project goals and objectives
   - Key architectural decisions
   - Technology stack and dependencies
   - Team conventions and patterns

2. **Current State**
   - Recently implemented features
   - Work in progress
   - Known issues and technical debt
   - Performance baselines

3. **Design Decisions**
   - Architectural choices and rationale
   - API design patterns
   - Database schema decisions
   - Security implementations

4. **Code Patterns**
   - Coding conventions used
   - Common patterns and abstractions
   - Testing strategies
   - Error handling approaches

5. **Agent Coordination History**
   - Which agents worked on what
   - Successful agent combinations
   - Agent-specific context and findings
   - Cross-agent dependencies

6. **Future Roadmap**
   - Planned features
   - Identified improvements
   - Technical debt to address
   - Performance optimization opportunities

Save this context in a structured format that can be easily restored and used by future agent invocations."

## Context Storage

The context will be saved to `.claude/context/` with:
- Timestamp-based versioning
- Structured JSON/Markdown format
- Easy restoration capabilities
- Context diffing between versions

## Usage Scenarios

This saved context enables:
- Resuming work after breaks
- Onboarding new team members
- Maintaining consistency across agent invocations
- Preserving architectural decisions
- Tracking project evolution

Context to save: $ARGUMENTS