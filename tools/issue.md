Please analyze and fix the GitHub issue: $ARGUMENTS. # 请分析并修复GitHub问题

Follow these steps: # 按照这些步骤：

# PLAN # 计划
1. Use 'gh issue view' to get the issue details # 使用'gh issue view'获取问题详情
2. Understand the problem described in the issue # 理解问题中描述的问题
3. Ask clarifying questions if necessary # 如有必要，提出澄清问题
4. Understand the prior art for this issue
- Search the scratchpads for previous thoughts related to the issue
- Search PRs to see if you can find history on this issue
- Search the codebase for relevant files
5. Think harder about how to break the issue down into a seriers of small, manageable tasks.
6. Document your plan in a new scratchpad
  - include the issue name in the filename
  - include a link to the issue in the scratchpad.

# CREATE
- Create a new branch for the issue
- Solve the issue in small, manageable steps, according to your plan.
- Commit your changes after each step.

# TEST
- Use playwright via MCP to test the changes if you have made changes to the UI
- Write tests to describe the expected behavior of your code
- Run the full test suite to ensure you haven't broken anything
- If the tests are failing, fix them
- Ensure that all tests are passing before moving on to the next step

# DEPLOY
- Open a PR and request a review.

Remember to use the GitHub CLI (`gh`) for all GitHub-related tasks.
