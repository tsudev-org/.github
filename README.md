# tsudev-org/.github

Organization-wide defaults for [tsudev-org](https://github.com/tsudev-org): the profile shown on the organization page
(`profile/README.md`) and the community health files (code of conduct, contributing guide, security policy, support,
issue and pull request templates, funding link) that GitHub applies to every repository without its own copy.

## Workflow dùng chung

| Tệp | Việc | Cách gọi |
| --- | --- | --- |
| `.github/workflows/virustotal.yml` | Quét tệp của một Release trên VirusTotal, ghi link báo cáo vào Release notes, có engine gắn cờ ⇒ Release về nháp (`DISTRIBUTION_TRUST.md` mục 3). Chưa có `VT_API_KEY` ⇒ bỏ qua, không chặn. | `uses: tsudev-org/.github/.github/workflows/virustotal.yml@<SHA>` - ví dụ đầy đủ ở đầu tệp |
