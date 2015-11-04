测试git提交编码问题
-- Add/modify columns 
alter table DPC_PM_CD add cd_status VARCHAR2(32);
-- Add comments to the columns 
comment on column DPC_PM_CD.cd_status
  is '拷贝状态';
