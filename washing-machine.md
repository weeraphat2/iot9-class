# Washing machine state

## START
topic:v1cdti/app/get/6310301022/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301022",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "START"
}

## READY
topic:v1cdti/app/get/6310301022/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301022",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "READY"
}

## FILLWATER
topic:v1cdti/app/get/6310301022/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301022",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "FILL_WATER"
}

## HEATWATER
topic:v1cdti/app/get/6310301022/model-01/sn-01
payload:{
    "action"    :   "get",
    "project"   :   "6310301022",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "HEAT_WATER"
}

## WASH
topic:v1cdti/app/get/6310301022/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301022",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "WASHING"
}

## RINSE
topic:v1cdti/app/get/6310301022/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301022",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "RINSE"
}

## SPIN
topic:v1cdti/app/get/6310301022/model-01/sn-01
payload:{
    "action"    :   "get",
    "project"   :   "6310301022",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "SPIN"
}

# Operation state

## DOORCLOSE
topic:v1cdti/app/set/6310301022/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301022",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "DOORCLOSE",
    "value"     :   "OFF"
}
## WATERFULLLEVEL
topic:v1cdti/app/get/6310301022/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301022",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "WATERFULLLEVEL",
    "value"     :   "FULL"
}
## TEMPERATUREREACHED
topic:v1cdti/app/set/6310301022/model-01/sn-01
payload:{
    "action"    :   "set",
    "project"   :   "6310301022",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "TEMPERATUREREACHED",
    "value"     :   "REACHED"
}


# FAULT state

## TIMEOUT
topic:v1cdti/app/set/6310301022/model-01/sn-01
payload:{
    "action"    :   "set",
    "project"   :   "6310301022",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULTSTATE",
    "value"     :   "TIMEOUT"
}
## OUTOFBALANCE
topic:v1cdti/app/set/6310301022/model-01/sn-01
payload:{
    "action"    :   "set",
    "project"   :   "6310301022",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "OUTOFBALANCE",
    "value"     :   "FAULT"
}

## MOTORFAILURE
topic:v1cdti/app/set/6310301022/model-01/sn-01
payload:{
    "action"    :   "set",
    "project"   :   "6310301022",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "MOTORFAILURE",
    "value"     :   "FAULT"
}

## FAULTCLEARED
topic:v1cdti/app/get/6310301022/model-01/sn-01
payload:{
    "action"    :   "get",
    "project"   :   "6310301022",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULTCLEARED",
    "value"     :   "READY"
}
