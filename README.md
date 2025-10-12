
# LucioBall
## ✓ Project Overview
<div align="center">

<table border="0" cellspacing="0" cellpadding="8" style="width: 100%; table-layout: fixed;">
  <tr>
    <td style="width: 20%; padding: 8px;"><strong>Project Name</strong></td>
    <td style="padding: 8px;">LucioBall - 오버워치 루시우 볼 모드 재현</td>
  </tr>
  <tr>
    <td style="padding: 8px;"><strong>Duration</strong></td>
    <td style="padding: 8px;">2025.09 ~ Development in Progress</td>
  </tr>
  <tr>
    <td style="padding: 8px;"><strong>Team Size</strong></td>
    <td style="padding: 8px;">Solo Development</td>
  </tr>
  <tr>
    <td style="padding: 8px;"><strong>Engine</strong></td>
    <td style="padding: 8px;">Unreal Engine 5</td>
  </tr>
  <tr>
    <td style="padding: 8px;"><strong>Language</strong></td>
    <td style="padding: 8px;">C++ & Blueprint</td>
  </tr>
  <tr>
    <td style="padding: 8px;"><strong>Version Control</strong></td>
    <td style="padding: 8px;">Git (main / feature branch workflow)</td>
  </tr>
  <tr>
    <td style="padding: 8px;"><strong>Purpose</strong></td>
    <td style="padding: 8px;">UE5 C++ 기반 물리·AI 중심 스포츠 게임 모드 구현</td>
  </tr>
</table>

</div>

---

## ✓ Tool & Skill
<div align="center">

  ### Game Development  
  ![Unreal Engine 5](https://img.shields.io/badge/Unreal%20Engine-5.0-blue?style=for-the-badge&logo=unrealengine&logoColor=white)
  ![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
  ![Blueprint](https://img.shields.io/badge/Blueprint-00599C?style=for-the-badge&logo=unrealengine&logoColor=white)

  ### Version Control  
  ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---


## Technical Architecture

**핵심 구현 사항:**

**AI 시스템 (`CEJ/Ai`):**
    *   **`AiLucio.cpp`**: 루시우 캐릭터의 AI를 구현하여 점프 포인트 찾기, 점프, 벽 타기, 낙하, 공 차기 등 다양한 상태를 처리합니다. 경로 찾기, 벽 추적, 공 접근 및 차기 방향 계산 로직을 포함하며, 유휴 및 이동 상태에 따른 애니메이션을 관리합니다.
    *   **`AiWallRunning.cpp`**: AI 캐릭터를 위한 벽 타기 메커니즘을 제공합니다. 벽 감지, 벽 타기 시작/중지, 벽에 붙는 힘 적용, 벽 타기 중 움직임 관리, 점프 포인트 감지 및 자동 점프 기능을 포함합니다.

이 프로젝트는 복잡한 게임 시스템 설계, AI 행동 트리 구현, 물리 기반 상호작용 처리, 그리고 동적 UI 업데이트 등 언리얼 엔진을 활용한 게임 개발의 다양한 측면을 성공적으로 다루었음을 보여줍니다.
