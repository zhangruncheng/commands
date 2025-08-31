Optimize application stack using specialized optimization agents: # 使用专业优化代理优化应用程序堆栈

[Extended thinking: This tool coordinates database, performance, and frontend optimization agents to improve application performance holistically. Each agent focuses on their domain while ensuring optimizations work together.] # [扩展思考：这个工具协调数据库、性能和前端优化代理，全面改善应用程序性能。每个代理专注于各自的领域，同时确保优化协同工作。]

## Optimization Strategy # 优化策略

### 1. Database Optimization # 数据库优化
Use Task tool with subagent_type="database-optimizer" to: # 使用带有subagent_type="database-optimizer"的Task工具：
- Analyze query performance and execution plans
- Optimize indexes and table structures
- Implement caching strategies
- Review connection pooling and configurations
- Suggest schema improvements

Prompt: "Optimize database layer for: $ARGUMENTS. Analyze and improve:
1. Slow query identification and optimization
2. Index analysis and recommendations
3. Schema optimization for performance
4. Connection pool tuning
5. Caching strategy implementation"

### 2. Application Performance
Use Task tool with subagent_type="performance-engineer" to:
- Profile application code
- Identify CPU and memory bottlenecks
- Optimize algorithms and data structures
- Implement caching at application level
- Improve async/concurrent operations

Prompt: "Optimize application performance for: $ARGUMENTS. Focus on:
1. Code profiling and bottleneck identification
2. Algorithm optimization
3. Memory usage optimization
4. Concurrency improvements
5. Application-level caching"

### 3. Frontend Optimization
Use Task tool with subagent_type="frontend-developer" to:
- Reduce bundle sizes
- Implement lazy loading
- Optimize rendering performance
- Improve Core Web Vitals
- Implement efficient state management

Prompt: "Optimize frontend performance for: $ARGUMENTS. Improve:
1. Bundle size reduction strategies
2. Lazy loading implementation
3. Rendering optimization
4. Core Web Vitals (LCP, FID, CLS)
5. Network request optimization"

## Consolidated Optimization Plan

### Performance Baseline
- Current performance metrics
- Identified bottlenecks
- User experience impact

### Optimization Roadmap
1. **Quick Wins** (< 1 day)
   - Simple query optimizations
   - Basic caching implementation
   - Bundle splitting

2. **Medium Improvements** (1-3 days)
   - Index optimization
   - Algorithm improvements
   - Lazy loading implementation

3. **Major Optimizations** (3+ days)
   - Schema redesign
   - Architecture changes
   - Full caching layer

### Expected Improvements
- Database query time reduction: X%
- API response time improvement: X%
- Frontend load time reduction: X%
- Overall user experience impact

### Implementation Priority
- Ordered list of optimizations by impact/effort ratio
- Dependencies between optimizations
- Risk assessment for each change

Target for optimization: $ARGUMENTS