# SyntaxAi
CatBoostModel (.cbm) trained on legit pvp

Input data: 

            float timestampMs,
            float targetSessionId,
            float hasTarget,
            float yaw,
            float pitch,
            float deltaYaw,
            float deltaPitch,
            float accelYaw,
            float accelPitch,
            float jerkYaw,
            float jerkPitch,
            float speed,
            float timeDeltaMs,
            float mouseSens,
            float gcd,
            float keyW,
            float keyA,
            float keyS,
            float keyD,
            float keySpace,
            float keyShift,
            float keySprint,
            float forwardSpeed,
            float sidewaysSpeed,
            float velX,
            float velY,
            float velZ,
            float horizontalSpeed,
            float moveAngle,
            float strafeAngle,
            float inputDriftYaw,
            float inputDriftPitch,
            float isSprinting,
            float isSneaking,
            float isOnGround,
            float isSwimming,
            float isInWater,
            float isSubmergedInWater,
            float targetDistance,
            float distX,
            float distY,
            float distZ,
            float targetYaw,
            float targetPitch,
            float deltaToTargetYaw,
            float deltaToTargetPitch,
            float targetVelX,
            float targetVelY,
            float targetVelZ,
            float targetIsSwimming,
            float targetIsInWater,
            float targetIsSubmergedInWater,
            float yawPitchRatio,
            float signsMatch,
            float bothMoving,
            float yawOnly,
            float pitchOnly
Output data: 

predDyStep
predDpStep
predSpeedYaw
predSpeedPitch
predHbYaw
predHbPitch
