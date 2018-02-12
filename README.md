# pysc2-learning
Pysc2 learning projects

### Simple Agent
https://chatbotslife.com/building-a-basic-pysc2-agent-b109cde1477c
```
python -m pysc2.bin.agent \
--map Simple64 \
--agent simple_agent.SimpleAgent \
--agent_race T
--max_agent_steps 0 \
--norender
```

### Smart Agent
https://chatbotslife.com/building-a-smart-pysc2-agent-cdc269cb095d
```
python -m pysc2.bin.agent \
--map Simple64 \
--agent smart_agent.SmartAgent \
--agent_race T \
--max_agent_steps 0 \
--norender
```

### Attack Agent
https://itnext.io/add-smart-attacking-to-your-pysc2-agent-17fd5caad578
```
python -m pysc2.bin.agent \
--map Simple64 \
--agent attack_agent.AttackAgent \
--agent_race T \
--max_agent_steps 0 \
--norender
```

### Sparse Agent
https://itnext.io/build-a-sparse-reward-pysc2-agent-a44e94ba5255
```
python -m pysc2.bin.agent \
--map Simple64 \
--agent sparse_agent.SparseAgent \
--agent_race T \
--max_agent_steps 0 \
--norender
```
